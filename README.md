# Read me

## Setup

- Add env-vars into `.env` file
- Create `/data/traefik/acme.json` file on the server
- Copy `dynamic_conf.yml` into `/data/traefik` dir
- Allow Ports 443 & 80 on the server (necessary for Traefik's LetsEncrypt)
