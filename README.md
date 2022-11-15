# Read me

## Setup

- Add env-vars into `.env` file
- Create `/data/traefik/acme.json` file on the server
- Copy `dynamic_conf.yml` into `/data/traefik` dir
- Allow Ports 443 & 80 on the server (necessary for Traefik's LetsEncrypt)
- Create `/data/webdav-config/user.passwd` file using the following example command

```bash
touch user.passwd
htpasswd -B user.passwd alice
htpasswd -B user.passwd bob
```

You may need the following package to use `htpasswd`;

```bash
apt-get install apache2-utils
```
