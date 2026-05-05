# Guitar Learning Hub - PWA Phone Ready

Bản này đã nâng cấp thành PWA, có thể cài như app trên điện thoại.

## File chính
- `index.html`: giao diện chính dạng app, tối ưu mobile.
- `manifest.webmanifest`: thông tin PWA.
- `sw.js`: service worker để cache và hỗ trợ offline sau lần tải đầu.
- `assets/icon-192.png`, `assets/icon-512.png`: icon app.
- `pages/`: 5 app/bài học HTML.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub.
2. Upload toàn bộ nội dung trong thư mục này.
3. Vào `Settings` > `Pages`.
4. Source chọn branch `main`, folder `/root`, rồi `Save`.
5. Mở link GitHub Pages bằng Chrome/Safari trên điện thoại.

## Cài lên điện thoại
### Android Chrome
Mở link web > bấm menu `⋮` > `Add to Home screen` hoặc `Install app`.

### iPhone Safari
Mở link web bằng Safari > bấm nút Share > `Add to Home Screen`.

## Ghi chú
- PWA cần chạy qua HTTPS. GitHub Pages đã có HTTPS nên dùng được.
- Offline hoạt động sau khi người dùng đã mở web ít nhất một lần để service worker cache file.
