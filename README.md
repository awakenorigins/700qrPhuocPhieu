# 700qrPhuocPhieu

Bản khóa để in **700 Phước Phiếu** của Tần Số Nacha.

## Phân phối

- 400 Trúc Duyên (`TD`, seq 0001–0400)
- 200 Kim Tâm (`KT`, seq 0001–0200)
- 100 Nguyên Niệm (`NN`, seq 0001–0100)

## Quy tắc bất biến sau khi in

1. Không xóa hoặc đổi `shortCode` trên Shlink.
2. Không đổi domain QR `https://qr.62.146.238.213.sslip.io`.
3. Có thể thay đổi **destination URL** trong Shlink khi website di chuyển; QR đã in vẫn giữ nguyên.
4. Không tái sử dụng một mã cho phiếu khác.
5. Trước mọi thay đổi, đối chiếu `manifest.csv` và `SHA256SUMS.txt`.

## Audit trước khi phát hành

- 700/700 QR giải mã đúng short URL.
- 700/700 short URL tồn tại trên Shlink.
- 700/700 destination URL trỏ đúng trang `/pp/<code>`.
- 0 mã trùng, 0 sequence thiếu.
- SHA-256 cho mọi PNG.

`manifest.csv` là danh sách thân thiện với Excel; `manifest.json` là bản máy đọc; `SNAPSHOT.json` ghi trạng thái khóa.
