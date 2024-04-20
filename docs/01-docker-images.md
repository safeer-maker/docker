# Docker Images

Docker container are build from images. Images are read only files. you can create multiple container from a single images. In case you need to change any code in you custon image. the latest verion of the image is created with new tag. So its important to tage your images. 

To list all the downloaded images use command `docker images`
``` bash
sa**@saf***:~/***/docker_prj/docker$ docker images
REPOSITORY              TAG            IMAGE ID       CREATED        SIZE
alpine                  20240329       49b3cb3043cd   3 weeks ago    7.74MB
alpine                  3.16.9         d49a5025be10   2 months ago   5.54MB
alpine                  latest         05455a08881e   2 months ago   7.38MB
phpmyadmin/phpmyadmin   latest         933569f3a9f6   9 months ago   562MB
mariadb                 10.6.4-focal   12e05d5da3c5   2 years ago    409MB
```

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

## Docker remove images

To remove docker old or unwanted images you can use `docker rmi` command.

``` bash
# to remove latest image by name
docker rmi alpine

# to remve spcific images with tag
docker rmi alpine:3.16.9

# it best to remove images using image id
docker rmi 05455a08881e
```


