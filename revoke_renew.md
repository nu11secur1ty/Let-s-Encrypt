### Manipulation, when the certificate is expired:
## Revoke
```bash
./certbot-auto revoke --cert-path /etc/letsencrypt/archive/yourdomain.com/yourCERT.pem
```
## Renew
```bash
./certbot-auto certonly --standalone -d yourdomain.com
```
