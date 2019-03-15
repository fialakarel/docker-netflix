# Chrome for Netflix 

Chrome for Netflix Docker image

## Usage

    docker run \
        --detach \
        --name netflix \
        --volume /tmp/.X11-unix:/tmp/.X11-unix \
        --env DISPLAY=$DISPLAY \
        --device /dev/snd \
        --volume /dev/shm:/dev/shm \
        fialakarel/netflix
