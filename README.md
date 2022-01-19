# Kubernetes Configurations
A bunch of configurations for getting Kubernetes up and running on 2+ Linux servers.

<br>
<br>

## Useful commands

<br>

### Allow user(s) to interface with Docker without sudo

<br>

```bash
#Should already exist after installing docker
sudo groupadd docker

sudo usermod -aG docker $USER

#Update docker group data
newgrp docker
```