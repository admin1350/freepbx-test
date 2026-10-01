# freepbx-test

`docker-compose`
```yaml
  services:
  freepbx:
    image: jmar71n/freepbx:latest
    container_name: freepbx
    restart: unless-stopped
    network_mode: "host"

    volumes:
      - freepbx_data:/data
    environment:
      - TZ=Europe/Moscow

volumes:
  freepbx_data:


```
