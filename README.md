# SSRF to Admin Interface Lab

Bài Lab giả lập lỗ hổng SSRF (Server-Side Request Forgery) cơ bản đến nâng cao. Truy cập vào trang web lab tại địa chỉ http://localhost:8080 
Mục tiêu: 
- Vượt qua blacklist để truy cập vào trang Admin nội bộ. tại http://localhost/admin/
- Thực hiện RCE và đọc flag
- Người chơi được cấp sẵn tài khoản người dùng thường steve:123456 để truy cập vào trang web

## Cách cài đặt

1. **Yêu cầu:** Máy đã cài sẵn `Docker` và `docker-compose`.
2. **Clone bài Lab:**
   ```bash
   git clone https://github.com/Kuri119/SSRF_Lab.git
   cd SSRF-Lab

## Hướng dẫn vận hành
1. **Dùng lệnh sau để bắt đầu dựng môi trường:**
   ```bash
   docker-compose up -d
2. **Dùng lệnh sau để xóa hoàn toàn môi trường:**
   ```bash
   docker-compose down -v
