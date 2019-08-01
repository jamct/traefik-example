# Traefik 2.0 and Let's Encrypt

Run this compose file on a machine with a public IP and a DNS A-record.

To get a certificate you have to change a few things:
* Admin Mail in docker-compose.yml
* Host names in static.yml
* Make sure to set file permissions on acme.json: `chmod 600 acme.json`
