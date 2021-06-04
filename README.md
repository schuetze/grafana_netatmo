# homeautomation

````
 podman run -d   --net=host   --restart=always   --name=homebridge   -e PUID=1001   -e PGID=1001   -e HOMEBRIDGE_CONFIG_UI=1   -e HOMEBRIDGE_CONFIG_UI_PORT=8080   -v /sata/homebridge/:/homebridge   oznu/homebridge
````
