# rest-api-mysql

-------------------------------------------------------------------------------------------------------------------------
เตรียมเครื่องมือ
MySQL เลือกใช้ Library ดัง mysqljs
ORM เลือกใช้ sequelize ที่เป็นที่นิยมมากเรื่องจัดการ Database
Web Framework เลือกใช้ ExpressJS ซึ่ง Mean Stack จะพูดถึงกันบ่อยมาก เพราะเป็น 1 ใน 4 จตุรเทพแห่ง Javascript เลย *MEAN
Editor เลือกใช้ VS Code
Postman เครื่องมือ API Client tool เอาไว้ Test ยิง API

-------------------------------------------------------------------------------------------------------------------------
git clone https://github.com/thering999/rest-api-mysql.git

cd rest-api-mysql

เริ่มสร้าง Table blog เก็บ Data ใน mysql จากไฟล์ db_medium.sql
 
จากนั้นใช้คำสั่ง

npm i

สั่ง nodemon app.js

-------------------------------------------------------------------------------------------------------------------------

เรียกข้อมูลของ Blog ทั้งหมด: [GET] http://localhost:3000/blog/find/all

เรียกข้อมูล Blog ด้วย Id: [GET] http://localhost:3000/blog/find/id/:id

สร้างข้อมูล Blog ใหม่: [POST] http://localhost:3000/blog/create

แก้ไขข้อมูล Blog เดิม: [PUST] http://localhost:3000/blog/update/:id

ลบข้อมูล Blog ในระบบ: [DELETE] http://localhost:3000/blog/delete/:id

-------------------------------------------------------------------------------------------------------------------------

Ref.https://poolsawat-com.medium.com/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-restful-api-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-expressjs-%E0%B8%81%E0%B8%B1%E0%B8%9A-mysql-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%81%E0%B8%B2%E0%B8%A3-orm-sequelizejs-1899de7f8757
