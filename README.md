![auto-wan-connect](https://github.com/2movn/auto-wan-conect/blob/main/auto-wan-conect.png)

# Cài đặt và kiểm tra
- Đầu tiên các bạn cần điền đầu đủ các cài đặt và thông tin PPOE. Mạng đã được Bridge từ nhà mạng hoặc tự Bridge Modem qua công Lan phù hợp.
- Địa chỉ mặc định `127.0.0.1:6996`

## 1. Kiểm tra server:
   
Truy cập địa chỉ server mặc định trên trình duyệt. Hiện thị `Server Worked !!!` Tức là đã hoạt động.

## 2. Tùy chỉnh port server:
   
Truy cập thư mục tool `setting` vào tệp `port.ini` tùy chỉnh port mà bạn cần.

# Hướng dẫn sử dụng API
Công cụ tích hợp api đơn giản với các chức năng như sau:
## 1. Start:
- Phương thức:
`GET`

- URL đích:
 ```127.0.0.1:6996/start```

- JSon trả về:
   
```
{
"status": 200,
"message": "Chạy thành công"
}
```
## 2. Stop:
- Phương thức:
`GET`

- URL đích:
 ```127.0.0.1:6996/stop```

- JSon trả về:
   
```
{
"status": 200,
"message": "Dừng thành công"
}
```
## 3. Reset:
- Phương thức:
`GET`

- URL đích:
 ```127.0.0.1:6996/reset```

- JSon trả về:
   
```
{
"status": 200,
"message": "Reset thành công"
}
```
