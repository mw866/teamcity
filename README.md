# TeamCity local
To build a local TeamCity Server and Agent environment for test purposes.

## Prequisites
1. [Docker Desktop](https://docs.docker.com/desktop/)
1. [Docker Compose](https://docs.docker.com/compose/install/)
## Quick start
1. Start TeamCity Server and Agent
```
docker-compose up -d
```

2. Monitor the logs
```
docker-compose logs -f
```

3. Access Teamcity Console by opening `http://localhost:8111/` in the browser.
