# NestJS Backend Store

[<img src="../img/nestjs.svg" width="72"/>](Nest.js)

## Description

Invoice backend repository (Code Invoice) made with Nest.js

**Important**: The Apache Kafka application, Golang (codebank) must be running first.

## Run the application

### Configure /etc/hosts

The communication between the applications takes place directly through the machine's network.
For this it is necessary to configure an address that all Docker containers can access.

Add to your /etc/hosts (for Windows the path is C:\Windows\system32\drivers\etc\hosts):
```
127.0.0.1 host.docker.internal
```
On all operating systems it is necessary to open the program to edit *hosts* as Administrator of the machine or root.

Run the commands:

```
docker-compose up
```

Access http://localhost:3002/credit-cards.

### Para Windows 

Lembrar de instalar o WSL2 e Docker. Vejo o vídeo: [https://www.youtube.com/watch?v=On_nwfkiSAE](https://www.youtube.com/watch?v=On_nwfkiSAE) 

Siga o guia rápido de instalação: [https://github.com/tluis9/wsl2-docker-quickstart](https://github.com/tluis9/wsl2-docker-quickstart) 