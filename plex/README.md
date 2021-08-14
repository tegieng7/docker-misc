## Usage

1. Get claim code at https://www.plex.tv/claim/
2. Add claim code to environment variable
3. Start container
4. Navigate to http://localhost:32400/web


```
export PLEX_CLAIM="<plex claim>"

docker-compose -f docker-compose.yml config

docker-compose up -d
```

## Docs

https://github.com/plexinc/pms-docker
