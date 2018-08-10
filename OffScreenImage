    private Image offScreenImage = null;

    public void update(Graphics g){
        if(offScreenImage == null)
            offScreenImage = this.createImage(700,800);

        Graphics gOff = offScreenImage.getGraphics();
        paint(gOff);
        g.drawImage(offScreenImage,0,0,null);
    }
