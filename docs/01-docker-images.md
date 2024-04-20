# Docker Images

Docker container are build from images. Images are read only files. you can create multiple container from a single images. In case you need to change any code in you custon image. the latest verion of the image is created with new tag. So its important to tage your images. 

## Docker offical iamges

[Dockerhub](https://hub.docker.com) contain the offical images from multiple software porviders, like ubuntu, alpine, nginx and many more. the developer maintain those images for lates relaesed.

You can download any images using `docekr pull` command
```bash
 # To download alpine image
 # https://hub.docker.com/_/alpine

 docker pull alpine

 # to download a specific verion of an image
 docker pull alpine:20240329
```



