# docker-odoo-nginx-postgresql
Odoo Docker Compose

change env-example to .env

please do chage the POSTGRES_PASSWORD in .env

# 流程想法筆記

git clone 下來後

先修改env檔案

必定要改的有 POSTGRES_PASSWORD CERTBOT_EMAIL CERTBOT_DOMAIN

先修改

第一次先docker-compose up

讓SERVERS先起來 然後申請SSL

在修改用https的default.conf檔案

裡面的
server_name domain.com 修改為你的網址
