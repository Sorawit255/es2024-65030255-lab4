# ใช้ official Nginx image เป็น base
FROM nginx:alpine

# คัดลอกไฟล์ index.html ไปยังไดเรกทอรีของ Nginx
COPY ../express/public /usr/share/nginx/html/

# เปิดพอร์ต 8080
EXPOSE 8080
