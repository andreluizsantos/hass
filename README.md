# hass
Repositório para configuração do ambiente Home Assistent


## Install Pre-requirements
```
apt-get update -y
apt install docker.io -y && apt install docker-compose -y
```

## Bring Up Docker
```
docker-compose up -d
```

## Remove Docker Volumes from Docker Compose File
```
docker-compose down --volumes
```

## Observação
```
Primeiro login no Grafana 
User:admin
Pass:admin