🔐 Simple Auth
🚀 Cách chạy
1. Vào thư mục chứa dự án
cd src/local_passport_website
2. Cài đặt dependencies bash Copy code: npm install express Basic Auth Chạy server bash Copy code: node app.js
Kiểm tra API
POST: http://localhost:3000/register
đăng ký với nội dung "{"username":"VoVanTuTai", "password":"12345"}"
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/register_web.png" />
sau khi đăng ký chuyển sang trang login
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/login.png" />
mongo sau khi đăng ký có tài khoản mang tên VoVanTuTai
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/local_passport_have_user.png" />
POST: http://localhost:3000/login
đăng nhập với nội dung "{"username":"VoVanTuTai", "password":"12345"}"
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/login.png" />
đăng nhập thành công sẽ chuyển sang trang welcome + tên user có chữ logout GET: http://localhost:3000/profile
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/login_success.png" />
lick logout http://localhost:3000/logout
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/local_passport_website/blob/main/Images_report/logout.png" />




