# Workaround to a long standing NGINX issue

I introduced this workaround on [stackoverflow](https://stackoverflow.com/a/45642689/4094353). This repo is just here to illustrate.

Install Docker and run `docker-compose up`. NGINX will be reachable over [http://localhost:8080](http://localhost:8080).

In the example I want to store two API versions in different folders separately from the main site.
- [/api/v1](http://localhost:8080/api/v1) in `/srv/api-v1/public/`
- [/api/v2](http://localhost:8080/api/v1) in `/srv/api-v2/public/`
