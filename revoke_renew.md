### Manipulation, when the certificate is expired:
## Revoke
./certbot-auto revoke --cert-path /etc/letsencrypt/archive/yourdomain.com/yourCERT.pem
## Renew
./certbot-auto certonly --standalone -d yourdomain.com

