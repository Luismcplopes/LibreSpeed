
# Linuxserver  
**(https://github.com/librespeed/speedtest**
**https://librespeed.org/)**

## Run it docker-compose 
```shell
git clone https://github.com/Luismcplopes/LibreSpeed.git
cd linuxserver
docker-compose up -d
```

## docker run
```shell
docker run --name libre_speed -e PUID=1000 -e PGID=1000 -e TZ=Europe/London -v ./LibreSpeed/config:/config -p 10101:80 --restart unless-stopped lscr.io/linuxserver/librespeed:latest
```

