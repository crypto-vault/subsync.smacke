# subsync.smacke (v0.3.2)

https://github.com/smacke/subsync (Docker version)

Share some movie/tv libraries to the docker when setup, for example:

/mnt/user/movies:/media/movies

Then you can call docker in your scripts as:

docker exec subsync /bin/bash -c "subsync '/media/movies/movie/movie.mkv' -i '/media/movies/movie/movie.srt' -o '/media/movies/movie/movie.out.srt'"
