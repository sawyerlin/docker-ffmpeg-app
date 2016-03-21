# docker-ffmpeg-app

### Add this piece of code into .bashrc file

```bash
alias docker-ffmpeg='docker run --rm -v $PWD:/opt sawyerlin/docker-ffmpeg-app
/usr/bin/ffmpeg
```

### Usage

    $ docker-ffmpeg -i in.mp4 ...
