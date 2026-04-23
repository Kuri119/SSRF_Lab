# SSRF to Admin Interface Lab

Bài Lab giả lập lỗ hổng SSRF (Server-Side Request Forgery) cơ bản đến nâng cao. 
Mục tiêu: 
- Vượt qua blacklist để truy cập vào trang Admin nội bộ. tại http://localhost/admin/
- Thực hiện RCE và đọc flag tại đấy

## Cách cài đặt

1. **Yêu cầu:** Máy đã cài sẵn `Docker` và `docker-compose`.
2. **Clone bài Lab:**
   ```bash
   git clone https://github.com/kuri119/SSRF-Lab.git
   cd SSRF-Lab

## Khởi chạy
   ```bash
   docker-compose up -d

## Dọn dẹp lab và cơ sở dữ liệu
   ```bash
   docker-compose down -v
