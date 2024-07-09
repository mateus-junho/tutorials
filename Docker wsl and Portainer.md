# Docker WSL + Portainer

- Install Ubuntu for Windows on Windows store
- Open Ubuntu terminal
- Install using the convenience script (without sudo su): [Convenience Script](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- Create a group and test docker command: [Manage Docker as a non-root user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)
- Install docker compose plugin: [Docker Compose Pluging](https://docs.docker.com/compose/install/linux/)
- Create a volume and up a Portainer Container: [Create portainer](https://docs.portainer.io/start/install-ce/server/docker/linux) 

If case of error `error getting credentials - could not connect: no such file or directory`

Try:
- Check your client config file: $HOME/.docker/config.json. You should find something like this in that file:
`"credsStore": "desktop",`

`sudo apt install gnome-keyring`
