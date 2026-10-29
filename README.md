# limdim.softie website

Website tĩnh (HTML + ảnh), không cần build.

## Cấu trúc
- `index.html`: toàn bộ trang (giao diện, sản phẩm, danh mục, giỏ đặt hàng qua Instagram)
- `images/`: toàn bộ ảnh (ảnh sản phẩm, catalog, booklet, feedback, logo)
- `.nojekyll`: để GitHub Pages phục vụ file đúng nguyên bản

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ `limdim-softie`).
2. Bấm **Add file → Upload files**, kéo thả **toàn bộ nội dung** trong thư mục này (`index.html`, thư mục `images`, `.nojekyll`) rồi **Commit changes**.
   Lưu ý: giữ nguyên thư mục `images` cạnh `index.html`.
3. Vào **Settings → Pages**, ở mục *Build and deployment* chọn **Deploy from a branch**, branch `main`, thư mục `/ (root)`, bấm **Save**.
4. Chờ 1–2 phút, web sẽ có địa chỉ dạng `https://<tên-github>.github.io/limdim-softie/`.

## Sửa sản phẩm / danh mục
Nút "Chỉnh sửa shop" chỉ hoạt động khi trang chạy trong claude.ai, trên GitHub nó sẽ tự ẩn.
Để sửa trên GitHub: mở `index.html`, tìm `const P=[` (danh sách sản phẩm: tên, giá nghìn đồng, ảnh, danh mục) và `const G={` (tên danh mục), sửa rồi commit.
Hoặc sửa bằng Claude rồi tải bản `index.html` mới.

## Ghi chú
- Font (Newsreader, Plus Jakarta Sans...) tải từ Google Fonts, cần có mạng.
- Mở `index.html` trực tiếp bằng cách bấm đúp trên máy vẫn xem được; ảnh nằm trong `images/`.
