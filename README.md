# Luyện KET – Từ vựng và Ngữ pháp

Trang web tĩnh (một file HTML) giúp ôn từ vựng và ngữ pháp cho kỳ thi Cambridge KET. Hỗ trợ giao diện sáng/tối và dùng được trên điện thoại.

## Chạy thử trên máy

Mở file `index.html` bằng trình duyệt là dùng được, không cần cài đặt gì.

## Đưa lên GitHub và bật GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `luyen-ket`).
2. Giải nén file zip, rồi đẩy nội dung lên:
   ```bash
   cd luyen-ket
   git init
   git add .
   git commit -m "Thêm trang luyện KET"
   git branch -M main
   git remote add origin https://github.com/<ten-ban>/luyen-ket.git
   git push -u origin main
   ```
3. Vào **Settings → Pages**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, rồi **Save**.
4. Sau ít phút, trang chạy tại `https://<ten-ban>.github.io/luyen-ket/`.

## Ghi chú

- Font chữ Be Vietnam Pro tải từ Google Fonts, nên cần có mạng để hiển thị đúng font (không có mạng vẫn dùng được với font hệ thống).
