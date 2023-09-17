# Hackintosh Laptop Acer Aspire 7 Gaming A715 42G R5 5500U
Opencore EFI Acer Aspire 7 Gaming A715 42G R5 5500U

## CẤU HÌNH

 D | Thông số
--- | ---
CPU | Ryzen 55500U 2.1GHz 
RAM | 8GB DDR4 2 khe (1 khe 8 GB + 1 khe rời) 3200 MHz
Ổ CỨNG | 512 GB SSD NVMe PCIe (Có thể tháo ra, lắp thanh khác tối đa 1 TB) Không hỗ trợ khe cắm SSD M2 mở rộng thêm. Không hỗ trợ khe cắm HDD
MÀN HÌNH | 15.6" Full HD (1920 x 1080) 144Hz
CARD MÀN HÌNH | Card rời GTX 1650 4GB
CỔNG KẾT NỐI | HDMI LAN (RJ45) USB 2.0, USB Type-C2 x USB 3.2, Jack tai nghe 3.5 mm
CHUỘT | ELAN I2C
BÀN PHÍM | PS2 (Có đèn bàn phím)
Ổ CỨNG | 512 GB INTEL 
WIFI | Mediatek wifi 6 mt7921 (Đã thay bằng Wifi 6 Intel AX210)

![THÔNG TIN](OVERVIEW.png?raw=true "THÔNG TIN")

## HOẠT ĐỘNG
- Bàn phím: Nhận đủ phím, các phím chức năng đủ (Fn + ...) (PS2).
- Chuột nhận đủ 4 ngón hoạt động tốt (HID I2C). 
- Kết nối màn hình rời qua HDMI tốt.
- Nếu dùng AppleALC.kext (layout-id=71) thì âm thanh nghe được, còn mic không dùng được (kể cả mic headphone lẫn mic in) chuyển đổi tự động được khi cắm headphone.
- Nếu dùng VoodooHDA.kext theo hướng dẫn trong https://www.insanelymac.com/forum/topic/314406-voodoohda-302/page/19/#comment-2756841 thì sửa được mic in (mic headphone jack 3.5mm không hoạt động), nhưng không tự động chuyển đổi speaker và headphones, lúc mở máy headphones luôn bật trước.
- Xem được phần trăm pin (dùng pin không dùng điện được khoảng hơn 2 giờ 30 phút).
- Sleep được (hoàn hảo kể cả chế độ ngủ đông hibernate mode = 25).
- Camera tốt
- Nhận đủ cổng USB
- Message, Facetime, app store chạy bình thường (lên sonoma app store bị lag).
- Dùng được mạng dây hoặc kết nối internet bằng usb smartphone
- Wifi 6 intel AX210 hoạt động bình thường, bluetooth dùng được (Các kext wifi và bluetooth từ bigsur đến sonoma đã được đặt MinKernel và MaxKernel trong config.plist nên không sợ trùng và panic cứ để vậy dùng muốn cài từ BigSur đến Sonoma khỏi phải mất công thay kext wifi intel)


## KHÔNG HOẠT ĐỘNG
- Card màn hình rời.


## HƯỚNG DẪN CHỈNH VOODOOHDA.KEXT NẾU BỊ RÈ TIẾNG HOẶC TIẾNG NHỎ
- Xem file Hướng dẫn dùng VoodooHDA.txt


## BIOS
- Chỉ chỉnh Boot Secure thành Disabled (Của tôi là vậy)


## XUNG NHỊP, NHIỆT ĐỘ, ĐIỆN
![THÔNG TIN](temperature.png?raw=true "THÔNG TIN")


