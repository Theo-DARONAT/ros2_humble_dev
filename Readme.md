# build Image

Run `sh build.sh`

> Warning
>
> This image takes around one hour to build.
> 
> If you don't need it, you can comment the ros2-desktop-dev

Once you build this image, you don't need to re-build it every time you want to
lunch a container.

# run docker container

Run `sh run.sh`

# how to have another terminal in the same docker container

Run `docker ps`

And then `docker exec -it [CONTAINER_ID] bash` with the id of your container.
