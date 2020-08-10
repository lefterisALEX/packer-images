## To build the image execute:
```
docker run --rm --privileged -v /dev:/dev -v ${PWD}:/build mkaczanowski/packer-builder-arm build -var wifi_name=SSID -var wifi_password=PASSWORD rasbian.json
```

