# nginx-php72
docker webserver

nginx+php7.2+mariadb+postgres

port ที่ใช้ เปลี่ยน port ก่อนใช้งาน ถ้า port 80,3306,5432 มีการใช้งานอยู่

nginx+php7.2 port 80

mariadb port 3306

postgres port 5432

เริ่มใช้งาน

docker-compose up -d

ทดสอบด้วยการเปิด browser เปิด url ด้านล่าง

http://localhost

เขียน code php ไว้ใน folder "www"

ตัวอย่าง

chown -R www-data.www-data joomla-dev

กำหนดสิทธ์ให้ folder project อยู่ในกลุ่มของ www-data 

เพื่อให้สามารถอัพโหลดไฟล์ได้โดยไม่ต้องกำหนดสิทธ์บาง folder เป็ย 777
