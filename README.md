## DOCKER MYSQL MULTI-ENV
A quick installation of a multiple mysql instances


## REQUIREMENTS
- docker
- docker-compose

## INSTALLATION:
```bash
# create env vars based on example
# ensure to replace with your desired credentials
cp .env.example .env

# pull and run mysql instances
docker-compose up -d
```