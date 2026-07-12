GREEN AURA - VÒNG QUAY MAY MẮN + MÃ QR
=====================================

1. CÁC FILE CHÍNH
- index.html      : Trang vòng quay thưởng.
- qr-code.html    : Trang tạo mã QR dẫn đến trang vòng quay.
- poster.html     : Trang poster A4 in ấn / standee có sẵn mã QR + phần thưởng.
- poster-a5.html  : Trang poster A5 (nhỏ gọn, vẫn rõ chữ).
- assets/         : Thư mục chứa logo, linh vật và hình phần thưởng.

2. HƯỚNG DẪN THAY HÌNH ẢNH (LOGO / QUÀ / VẬT PHẨM)
Các file trong assets/ đã được đặt tên rõ ràng. Bạn chỉ cần thay file cùng tên
bằng ảnh thật (PNG/JPG), giữ nguyên tên file:

  assets/logo-green-aura.png     -> Logo chính Green Aura (đã có từ PDF)
  assets/logo-icon.png           -> Biểu tượng hoa/icon (đã có từ PDF)
  assets/mascot.png              -> Linh vật GreenAura (đã có từ PDF)
  assets/prize-keychain.svg      -> Móc khóa          (placeholder, hãy thay)
  assets/prize-fan.svg           -> Quạt cầm tay      (placeholder, hãy thay)
  assets/prize-voucher.svg       -> Voucher           (placeholder, hãy thay)
  assets/prize-bear.svg          -> Gấu bông          (placeholder, hãy thay)
  assets/prize-discount.svg      -> Giảm 10%          (placeholder, hãy thay)
  assets/prize-luck.svg          -> May mắn lần sau   (có thể giữ hoặc thay)

Gợi ý: nếu muốn dùng ảnh PNG/JPG, chỉ cần xóa file .svg và đặt file ảnh mới
vào cùng tên (ví dụ: prize-keychain.png). Trang web sẽ tự động hiển thị.

3. MÀU SẮC THƯƠNG HIỆU (theo Brand Guideline PDF)
- Forest Green / Deep Green  : #2B4A32
- Olive Green / Moringa Green: #8D9F4D
- Sage Green / Mint          : #9EC8B2
- Warm Beige / Sand Beige    : #CBB8A6
- Taupe Brown / Earth Brown  : #9F8873
- Golden Yellow / Aura Gold  : #F6D54C
- Blush Pink / Aura Pink     : #FFB2E1
- Ivory White / Cream White  : #FCF8F3

4. FONT CHỮ
- Tiêu đề: Playfair Display (tương đương phong cách Malik trong guideline).
- Nội dung: Mali (có sẵn trên Google Fonts).

5. CÁC PHẦN THƯỞNG TRÊN VÒNG QUAY
1. Móc khóa Green Aura
2. Quạt cầm tay
3. Voucher mua sắm
4. Gấu bông Green Aura
5. Giảm 10% cho hóa đơn tiếp theo
6. Chúc bạn may mắn lần sau

6. TEST TRÊN MÁY TÍNH
- Mở thư mục C:\GreenAura bằng VS Code.
- Cài và bật extension Live Server.
- Chuột phải index.html > Open with Live Server.

7. QUÉT QR BẰNG ĐIỆN THOẠI TRONG CÙNG WIFI
- Không dùng địa chỉ 127.0.0.1 hoặc localhost vì điện thoại sẽ không truy cập được.
- Mở Command Prompt, gõ: ipconfig
- Tìm IPv4 Address, ví dụ: 192.168.1.10
- Trên máy tính, mở một trong các trang sau để lấy/làm mã QR:
    http://192.168.1.10:5500/qr-code.html   (trang QR đơn giản)
    http://192.168.1.10:5500/poster.html    (poster in ấn có QR)
- Các trang này sẽ tự tạo mã QR dẫn tới:
    http://192.168.1.10:5500/index.html
- Điện thoại và máy tính phải dùng cùng mạng Wi-Fi.
- Nếu không mở được, cho phép VS Code/Live Server qua Windows Firewall.

8. DÙNG CHÍNH THỨC
- Đưa toàn bộ thư mục lên hosting, Netlify, Vercel hoặc máy chủ của bạn.
- Mở qr-code.html hoặc poster.html bằng tên miền chính thức.
- Mã QR sẽ tự động trỏ đến index.html trên cùng tên miền.

9. CÁCH MÃ QR DẪN ĐẾN VÒNG QUAY
- Mã QR chứa đường link đến file index.html.
- Khi khách quét bằng điện thoại, trình duyệt mở link đó và hiện ra trang quay.
- Ví dụ link đúng: https://tenmien.com/index.html
- Ví dụ link sai (chỉ xem trên máy tính): file:///C:/GreenAura/index.html

LƯU Ý
Mã QR chỉ có thể đưa ngườì dùng tới trang web khi trang đó có một URL mà
điện thoại truy cập được. Đường dẫn C:\GreenAura là đường dẫn cục bộ trên
máy tính và không thể dùng trực tiếp làm mã QR cho khách hàng.
