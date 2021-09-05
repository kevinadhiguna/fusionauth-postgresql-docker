# FusionAuth PostgreSQL - docker-compose

🔒 FusionAuth (Authentication and Authorization service) with PostgreSQL powered by docker-compose.
<br/>
<br/>
Don't waste your time on authentication and authorization...

## Prerequisites :

You should have [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/) in your computer.

## How to Run :

1) Clone this repository :
```bash
git clone https://github.com/kevinadhiguna/fusionauth-postgresql-docker
```

2) Create `.env` file :
```bash
cp .env.example .env
```

Then please fill the `.env` file.

3) Run your app with `docker-compose` :
```bash
docker-compose -f fusionauth-postgresql.yaml up
```

You can visit your app at `http://localhost:9011` in your browser.

<br/>

[![Visits Badge](https://badges.pufler.dev/visits/kevinadhiguna/fusionauth-postgresql-docker)](https://github.com/kevinadhiguna)
