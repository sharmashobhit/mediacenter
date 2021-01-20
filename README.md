# Self hosted Media server and download automator


| Application | Port(s) |
|-------------|---------|
| Radarr      | 7878    |
| Sonarr      | 8989    |
| Lidarr      | 8686    |
| Deluge      | 8112    |
| Bazarr      | 6767    |
| Jackett     | 9117    |


## How to use

Download the repo and run it using `docker-compose`

- Copy the `.env_template` file to `.env` and edit the variables 

### Prerequisites

- Docker
- Docker Compose

### Commands

_To run all the services_

```
docker-compose up -d
```

_Running the samba server_

```
docker-compose -f local-sharing-docker-compose.yml up -d 
```
