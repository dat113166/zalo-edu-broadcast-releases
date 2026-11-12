# Sổ gửi phụ huynh

Ứng dụng chạy trên máy tính Windows của giáo viên. Sau mỗi buổi học, bạn soạn cho từng học sinh một chuỗi tin (chữ xen ảnh), xem lại một lần, rồi ứng dụng tự gửi vào nhóm Zalo riêng của từng học sinh.

Kho này chỉ chứa các bản phát hành.

## Tải về

1. Vào [bản mới nhất](../../releases/latest), tải file `SoGuiPhuHuynh-<bản>.zip`.
2. Giải nén ra một thư mục cố định trên máy (ví dụ `D:\SoGuiPhuHuynh`).
3. Bấm đúp `Mo So gui phu huynh.bat`. Không cần cài thêm gì.
4. Đọc `HUONG-DAN.txt` trong thư mục vừa giải nén.

## Cập nhật

Ứng dụng tự kiểm tra bản mới. Khi đầu trang hiện "Có bản mới", bấm vào đó để xem thay đổi rồi bấm "Cập nhật ngay". Lớp, học sinh, ảnh và lịch sử gửi của bạn được giữ nguyên.

Các file `cap-nhat-<bản>.zip` và `phien-ban.json` trong mỗi bản phát hành là để ứng dụng tự tải, bạn không cần tải tay.

## Lưu ý

- Dữ liệu của bạn (lớp, học sinh, ảnh, phiên đăng nhập Zalo) chỉ nằm trên máy bạn, trong thư mục `du-lieu`.
- Ứng dụng gửi tin qua thư viện không chính thức [`zca-js`](https://github.com/RFS-ADRENO/zca-js). Zalo không cho phép tự động hóa tài khoản cá nhân, nên tài khoản có thể bị hạn chế hoặc khóa. Bạn tự chịu rủi ro này khi dùng.
