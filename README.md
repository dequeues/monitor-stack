Just my grafana monitoring stack, nothing fancy. 


# Notes
If you are running this stack on Windows, you will need to create a docker mount that cadvisor will use as a volume.
```
sudo mount -t drvfs '\\wsl$\docker-desktop-data\data\docker' /mnt/windows_docker
```
Then uncomment the volume in docker-compose.yml for cadvisor.

Here's a cute kitty, since this readme is so bland.

![cat](https://cataas.com/cat)

_[source](https://cataas.com/cat)_
