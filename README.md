# NGINX with auto-renewing Let's Encrypt certificates

1. Fill init-letsencrypt.sh with email and domains (lines 8 & 11)
2. Add server-name in /data/nginx/app.conf
3. Execute the BASH `bash init-letsencrypt.sh`
4. `docker-compose up -d`
