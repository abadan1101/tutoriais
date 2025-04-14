
======================    PM2     =======================
pm2 start index.js --name 'backend'
pm2 start package.json --name 'frontend'
pm2 start 'backend'
pm2 stop all
pm2 stop 'backend'
pm2 delete all
pm2 reload all
pm2 reload 'backend'
pm2 list
=========================================================

======================    NGINX     =====================
sudo apt install certbot python3-certbot-nginx
sudo systemctl reload nginx
sudo nginx -t
=========================================================

======================    LINUX     =====================
https://m.youtube.com/watch?v=CP8-s8aP5Uw
=========================================================


