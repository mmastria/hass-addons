### Instalar ssh client no supervisor
```
ssh homeassistant
sudo su -
docker exec -it hassio_supervisor /bin/bash
apk add openssh-client
ssh-keygen
ssh copy-id homeassistant@172.24.24.4
```

### Adicionar novo Repositório

HA -> Settings -> Add-ons -> Add on Store -> Repositories:

**ssh://homeassistant@172.24.24.4:/volume1/repos/z2m-mastria**

### Instalar Add-On
- Zigbee2MQTT HomeLab
- Zigbee2MQTT Sala
- Zigbee2MQTT Oficina




