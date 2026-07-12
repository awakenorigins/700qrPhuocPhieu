# 700qrPhuocPhieu

Bản khóa **CHÍNH XÁC BIT-FOR-BIT** của 700 Phước Phiếu đã gửi in của Tần Số Nacha.

## Phân phối

- 400 Trúc Duyên (`TD`, seq 0001–0400)
- 200 Kim Tâm (`KT`, seq 0001–0200)
- 100 Nguyên Niệm (`NN`, seq 0001–0100)

## Quy tắc bất biến sau khi in

1. **KHÔNG BAO GIỜ tái sinh, chỉnh sửa hoặc thay thế PNG QR đã in.**
2. Không xóa hoặc đổi `shortCode` trên Shlink.
3. Không đổi domain QR `https://qr.62.146.238.213.sslip.io`.
4. Có thể thay đổi **destination URL** trong Shlink khi website di chuyển; QR đã in vẫn giữ nguyên.
5. Không tái sử dụng một mã cho phiếu khác.
6. Trước mọi thay đổi, đối chiếu `manifest.csv` và `SHA256SUMS.txt`.

## Audit trước khi phát hành

- 700/700 PNG là file gốc chính xác đã gửi in.
- 693/700 được OpenCV giải mã; 7 file còn lại vẫn giữ nguyên tuyệt đối vì không được phép đổi hình sau khi gửi in.
- 700/700 short URL tồn tại trên Shlink.
- 700/700 destination URL trỏ đúng trang `/pp/<code>`.
- 0 mã trùng, 0 sequence thiếu.
- SHA-256 cho mọi PNG.

`manifest.csv` là danh sách thân thiện với Excel; `manifest.json` là bản máy đọc; `SNAPSHOT.json` ghi trạng thái khóa.
