HƯớng dẫn sửa dụng và cài đặt:
I./File ajax.html 

Bước 1: truy cập link:https://mockapi.io/ tạo mới 1 projects
Bước 2: chọn chỉnh sửa projects có các cột name, city, cath, BS, noun
Bước 3: coppy links mockapi của cá nhân vào file ajax.html thay link vào dòng:

                url: 'https://6214b27889fad53b1f1bc406.mockapi.io/SanPham'

II./file data.php
Bước 1 giải nén file fake-db.rar

Bước 2. chạy MySQL tao database: fake_db
Bước 3. load sql tao table: user_fake

CREATE TABLE IF NOT EXISTS `user_fake` (
  `id` int(10) NOT NULL AUTO_INCREMENT,
  `name` varchar(100) NOT NULL,
  `email` varchar(50) NOT NULL,
  `phone` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

Bước 4. Dat sourcecode fake-db trong documentRoot (wamp\www,...), chay localhost...

(Thay doi so dong can them trong index.php - neu can)

Bước 5 :thay password(tuỳ theo máy) trong file data.php
