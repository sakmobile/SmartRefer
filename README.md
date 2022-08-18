# smart-refer
# ตั้งค่า

config.api

- ติดต่อฐานจ้อมูล HIS

DB_HOST=localhost

DB_CLIENT=mysql2

DB_PORT=3306

DB_NAME=his

DB_USER=his

DB_PASSWORD=12345678

- รหัสสถานบริการ 

HIS_CODE=27967

- Api เซื่อมต่อ Server กลาง

SERV_API_URL=http://xxxxxxxxx:xxx

# Setup

docker network create kong-network

docker-compose up -d

# Open

http://localhost:8080


# Update

docker-compose pull

docker-compose down

docker-compose up -d
