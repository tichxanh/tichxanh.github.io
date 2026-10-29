# tichxanh.github.io

Website **Tích Xanh** – dịch vụ thông báo website thương mại điện tử và xây dựng website bán hàng đúng chuẩn, theo Luật Thương mại điện tử số 122/2025/QH15 và Nghị định 248/2026/NĐ-CP.

Địa chỉ: **https://tichxanh.github.io**

## Đưa lên GitHub Pages

Địa chỉ `tichxanh.github.io` chỉ hoạt động khi:

1. Có tài khoản (hoặc tổ chức) GitHub tên đúng là **`tichxanh`**.
2. Trong tài khoản đó có repo **công khai** tên đúng là **`tichxanh.github.io`**.
3. Các file trong thư mục này nằm ở gốc nhánh `main`.

Sau khi đẩy code lên, vào **Settings → Pages**, mục *Build and deployment* chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`. Website chạy sau 1–2 phút.

## Các file

| File | Vai trò |
|---|---|
| `index.html` | Toàn bộ website (HTML, CSS, JS trong một file, không cần build) |
| `404.html` | Trang báo không tìm thấy |
| `og-image.jpg` | Ảnh xem trước khi chia sẻ link lên Zalo, Facebook |
| `favicon.svg`, `apple-touch-icon.png` | Biểu tượng tab trình duyệt và màn hình điện thoại |
| `robots.txt`, `sitemap.xml` | Hỗ trợ Google lập chỉ mục |
| `.nojekyll` | Báo GitHub Pages phục vụ file nguyên trạng |

## Thông tin liên hệ

Khai báo trong khối `CONTACT` ở phần script của `index.html`:

```js
const CONTACT = {
  phone: '0915 506 706',
  zalo: 'https://zalo.me/0915506709',
  messenger: 'https://m.me/quynhtrangkt',
  facebook: 'https://facebook.com/quynhtrangkt'
};
```

Sửa khối này khi cần đổi số điện thoại hoặc kênh liên hệ.

## Trợ lý tư vấn

Trên GitHub Pages, trợ lý trả lời từ bộ Hỏi đáp có căn cứ điều khoản và gợi ý mẫu website theo ngành hàng. Muốn trả lời bằng AI cần nối thêm một API phía máy chủ.

## Tối ưu đã có

- Điểm Core Web Vitals mức Tốt: LCP 0,62 s (điện thoại), CLS 0, INP dưới 60 ms
- Dữ liệu cấu trúc cho Google: dịch vụ chuyên nghiệp và bộ Hỏi đáp (FAQPage)
- Thẻ chia sẻ mạng xã hội, đường dẫn chuẩn (canonical), sitemap
- Giao diện sáng/tối, đạt tương phản chữ, có đường tắt bàn phím, tự giảm chuyển động khi người dùng bật chế độ giảm chuyển động

---
Nội dung pháp lý mang tính tham khảo. Việc xác nhận thông báo thuộc thẩm quyền của UBND cấp tỉnh.
