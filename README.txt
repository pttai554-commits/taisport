SPORTSTORE V2 — CỬA HÀNG ĐỒ THỂ THAO
=====================================

CÁCH CHẠY LOCALHOST 3000
------------------------
1. Giải nén file ZIP này.
2. Mở thư mục bằng VS Code (cài extension "Live Server" nếu chưa có).
3. Chuột phải vào index.html -> Open with Live Server.
4. Web chạy ở địa chỉ: http://127.0.0.1:3000
   (file .vscode/settings.json đã cài sẵn port 3000)

CẤU TRÚC GÓI
------------
- index.html : toàn bộ website (10 trang: Trang chủ, Cửa hàng, Chi tiết sản phẩm,
  Giỏ hàng, Thanh toán, Giới thiệu, Góc tư vấn, Chính sách, Liên hệ, Tải source)
- assets/    : ảnh sản phẩm thật của website
- README.txt : file này

TÍNH NĂNG
---------
- 16 sản phẩm, 4 bộ môn: cầu lông, bóng đá, pickleball, giày thể thao
- Điều hướng bấm được mọi trang: menu, footer, thẻ sản phẩm, nút mua
- Tìm kiếm có gợi ý sản phẩm, lọc theo môn/giá, sắp xếp, yêu thích, Flash Sale đếm ngược
- Giỏ hàng, mã SPORT10 giảm 10%, miễn phí ship từ 499.000đ
- Thanh toán kiểm tra dữ liệu, đặt hàng ra mã đơn
- Bán hàng tự động: dải AUTO 24/7, cấp mã đơn + tự tính ship/giảm giá + dự kiến ngày nhận tự động
- Font mới: Archivo (tiêu đề) + Plus Jakarta Sans (nội dung) + IBM Plex Mono (giá, mã đơn)
- Responsive PC + mobile, tone chủ đạo #f63a00, nền sáng

Lưu ý: giỏ hàng/đơn hàng bản demo chỉ lưu trong phiên mở trang (chưa có backend).
