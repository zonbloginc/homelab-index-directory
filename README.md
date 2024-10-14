# homelab-index-directory
Homelab Directory


Cd to /data/compose/{number}/ and run:

```
mkdir -p ./stack/certs
openssl req -x509 -nodes -days 365 -newkey rsa:2048 \
    -keyout ./stack/certs/apache.key \
    -out ./stack/certs/apache.crt \
    -subj "/CN=localhost"

```
