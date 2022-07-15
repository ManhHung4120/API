# RestAPI với Flask, Sqlite3
![image](https://user-images.githubusercontent.com/94128344/179167345-a5d3ddf2-59cf-493d-a95f-2f7adf6c7fc9.png)
Sử dụng Postman để test request GET, POST, PUT, DELETE

1. CSDL gồm 1 bảng User với các trường id, username, password và email
2. Test :
Đăng nhập, gửi request với method POST và username, password dưới dạng JSON :
- Nếu sai thì gửi trả về trang đăng nhập
![image](https://user-images.githubusercontent.com/94128344/179169228-932b8b9f-da20-4556-9b66-cf206ca12773.png)
- Nếu đúng thì chuyển về trang thành công
![image](https://user-images.githubusercontent.com/94128344/179169550-6ac9f6dd-7ea3-4298-a36c-3400cb8575b3.png)
- Gửi 1 request với method POST ở đường dẫn http://127.0.0.1:5000/user với username, password, email để tạo thêm 1 user mới và nhận về list tất cả tài khoản hiện có
![image](https://user-images.githubusercontent.com/94128344/179170195-d940b437-2534-4cf3-8bc6-32c14ff3e6e9.png)
