# Happy You
Final ASE Project

## Project Status
Status: **OPEN**\
Completion: **50%**\

## Project Description
Happy You is a website for booking calender and buy medicine

## Tools of Development
- HTML 5
- CSS 3
- JavaScript
- PHP 8.0.9
- MySQL Database
- Bootstrap 5.1.3
- Omise API Version 2020-05-29(not yet)

## Footnote
- Food images included in the img folder are downloaded from freepik.com and VietNamFood.com page
- To install the Itec Canteen app, download and install XAMPP, download this repository and put into directory (C:/xampp/htdocs/), import database and name it eaterio in phpMyAdmin (http://localhost/phpmyadmin) using file itec.sql, start Apache and MySQL services, then run and access by using web browser (http://localhost/PHP-Project/) and enjoy.
- You can register for the customer account and log in. To log in with shop account, press the log in with shop account under login page. Add shop account using the admin mode. Access admin mode by clicking at the first name in the footer at the customer log in page. You can look up

## Members
2059032 - Nguyễn Trần Nhật Phương  
2059027 - Bùi Quang Minh 
2059025 - Phạm Thái Linh
20590** - Trầm Thị Tuyết Thanh
20590** - Văn Công Gia Hưng

## How to run
This project uses PHP to connect to MySQL server, and is simulating school canteen management system. If you do not want to configure too much, just download xampp latest version from: https://www.apachefriends.org/download.html and use 127.0.0.1 to visit index.html. However, if you want to use localhost/ to visit your project, the following configurations are needed:

1.open xampp root directory -> apache -> conf -> httpd.conf, search for "DocumentRoot" and change the address to your project root directory; also, you would find <Directory> tag below, change the address to your project root.

2.Find a file named hosts in your C: drive and add one line "127.0.0.1  localhost" to the last line of the file. (How to find the file? Google it; but if you are using the lastest version of Win10 then the address would be "C:\Windows\WinSxS\amd64_microsoft-windows-w..ucture-other-minwin_31bf3856ad364e35_10.0.16299.15_none_582bc968d636655c\hosts") 
  
localhost/main.php (Page for manager)

function:
manage employees

localhost/staff.php (Page for staff)

function:
manage orders

localhost/order.php (Page for customer)

function:
make orders

Also, thanks for FPDF and its authors http://www.fpdf.org/, I could be able to generate customer order in PDF format in my project.