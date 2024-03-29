# FusionAuth PostgreSQL - docker-compose

🔒 FusionAuth (Authentication and Authorization service) with PostgreSQL powered by docker-compose.

<br />

<img src="https://s9.gifyu.com/images/fa.png" alt="fa.png" border="0" />

Don't waste your time on authentication and authorization...

<br />

## Prerequisites :

You should have [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed on your computer.

<br />

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

3) Run your app with `docker-compose` (in detached mode, you will not be seeing logs of your app) :
```bash
docker-compose -f fusionauth-postgresql.yml up -d
```

If you want to see the logs while running your app, run it with :
```bash
docker-compose -f fusionauth-postgresql.yml up
```

You can visit your app at `http://localhost:9011` in your browser.

<br />

![Hello !](https://api.visitorbadge.io/api/VisitorHit?user=kevinadhiguna&repo=fusionauth-postgresql-docker&label=thanks%20for%20dropping%20in%20!&labelColor=%23000000&countColor=%23FFFFFF)
