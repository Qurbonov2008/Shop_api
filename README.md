# Shop_api
in Laravel Apii

API Endpointlar
Method	Endpoint	Tavsif	Ruxsat

GET	/api/products	Barcha mahsulotlarni ro‘yxati	Hammaga

GET	/api/products/{id}	Bitta mahsulot haqida ma’lumot	Hammaga

POST	/api/products	Yangi mahsulot qo‘shish	Admin

PUT	/api/products/{id}	Mahsulotni yangilash	Admin

DELETE	/api/products/{id}	Mahsulotni o‘chirish	Admin

GET	/api/categories	Kategoriyalar ro‘yxati	Hammaga

POST	/api/orders	Yangi buyurtma yaratish	Mijoz

GET	/api/orders/{id}	Buyurtma haqida ma’lumot	Mijoz/Admin

POST	/api/auth/register	Ro‘yxatdan o‘tish	Hammaga

POST	/api/auth/login	Tizimga kirish	Hammaga

GET	/api/search?query=phone	Mahsulotlarni qidirish	Hammaga