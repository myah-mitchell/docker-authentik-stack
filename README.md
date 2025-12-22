# Docker Authentik Stack


## Created needed folders

```bash
mkdir -p /opt/docker/volumes/authentik/authentik-data/media
mkdir -p /opt/docker/volumes/authentik/authentik-data/templates
mkdir -p /opt/docker/volumes/authentik/authentik-data/certs
mkdir -p /opt/docker/volumes/authentik/geoip-data
chmod -R 770 /opt/docker/volumes/authentik/*
sudo chown -R $USER:101000 /opt/docker/volumes/authentik
```

