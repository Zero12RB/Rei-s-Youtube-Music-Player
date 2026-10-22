# 🎵 Rei's Youtube Music Player (Off-Screen Cast Receiver)

![PowerShell](https://img.shields.io/badge/PowerShell-5.1+-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Một ứng dụng chạy trên nền Windows cho phép biến máy tính của bạn thành thiết bị phát nhạc/video từ điện thoại (thông qua tính năng **YouTube TV Cast / Link with TV code**) mà **hoàn toàn không hiển thị cửa sổ YouTube trên màn hình**.

---

## ✨ Tính năng nổi bật (Key Features)

* 🚀 **Khởi chạy siêu tốc & Tối ưu hóa:** Khởi chạy cửa sổ YouTube TV ngầm ngay từ gốc mà không gây chớp/giật màn hình.
* 🙈 **Ẩn hoàn toàn Off-Screen:** Dịch chuyển vị trí cửa sổ YouTube TV ra ngoài tọa độ hiển thị của màn hình, giúp bạn làm việc, chơi game không bị gián đoạn.
* 🎧 **Hook Event Win32 Real-time:** Tự động bắt sự kiện tạo cửa sổ YouTube mới và đẩy ngay ra ngoài màn hình trong `0ms`.
* ⚡ **Tiết kiệm tài nguyên:** Tự động tối ưu hóa hai tiến trình Edge song song (loại bỏ thẻ dư thừa/trùng lặp) giúp tiết kiệm dung lượng RAM.
* 🔔 **Tích hợp System Tray:** Thu gọn ứng dụng xuống khay hệ thống (System Tray) gọn gàng.
* ⚙️ **Chế độ Auto-Hide:** Tự động ẩn toàn bộ giao diện và cửa sổ phát ngay khi khởi động Windows.

---

## 📋 Yêu cầu hệ thống (Requirements)

* **Hệ điều hành:** Windows 10 / Windows 11
* **Trình duyệt:** Microsoft Edge (Được cài đặt mặc định trên Windows)
* **Extension Yêu cầu :** [Youtube TV ON PC](https://chromewebstore.google.com/detail/jldjbkccldgbegjpggphaeikombjmnkh?utm_source=item-share-cb) [UBlock Origin](https://ublockorigin.com/)
* **Quyền hạn:** Chạy dưới quyền **Administrator** 

---

## 🚀 Hướng dẫn sử dụng (Usage)

### 1. Cài đặt Extension + Khởi chạy script
Cài đặt 2 Extension này cho trình duyệt Edge : [Youtube TV ON PC](https://chromewebstore.google.com/detail/jldjbkccldgbegjpggphaeikombjmnkh?utm_source=item-share-cb) [UBlock Origin](https://ublockorigin.com/)
Nhấp chuột phải vào file `YTHeadless.exe`, Chờ cho tới khi 2 cửa sổ mở xong
Tại đây sẽ xuất hiện Panel , chọn `1. Open youtube`

### 2. Kết nối với Điện thoại (Cast)
1. Mở ứng dụng YouTube trên điện thoại của bạn.
2. Nhấn vào biểu tượng **Cast (Phát lên TV)**.
3. Chọn **Link with TV Code** (Liên kết bằng mã TV).
4. Mở cửa sổ YouTube bằng nút **`3. Show YouTube Window`** trên panel ứng dụng để lấy mã 12 chữ số (hoặc quét QR) trong mục *Settings > Link with TV code*.
5. Sau khi kết nối thành công, nhấn **`2. Hide YouTube Off-Screen`** hoặc **`4. Hide Panel to Tray`** để ẩn hoàn toàn ứng dụng.

---

## 🛠️ Cấu trúc tùy chọn trên Panel

| Nút bấm | Chức năng |
| :--- | :--- |
| **1. Open youtube** | Khởi chạy giao diện YouTube TV bằng Microsoft Edge. ( dùng để đăng nhập + Pair thiết bị ) |
| **2. Hide YouTube Off-Screen** | Đẩy cửa sổ YouTube đang phát ra ngoài tọa độ màn hình. |
| **3. Show YouTube Window** | Đưa cửa sổ YouTube trở lại màn hình chính để điều chỉnh/cài đặt. |
| **4. Hide Panel to Tray** | Thu nhỏ bảng điều khiển xuống khay hệ thống (System Tray). |
| **Auto-Hide on Launch** | Bật/Tắt chế độ tự động ẩn hoàn toàn ngay khi khởi động. |

---

## 💬 Liên hệ & Hỗ trợ (Contact & Support)

* **Author:** Isekairei
* **Discord:** `Isekairei`
* **Community:** [Discord.gg/acn](https://discord.gg/acn)

> ⚠️ **Lưu ý:** Phần mềm này được phát triển hoàn toàn miễn phí. Nếu bạn mua phần mềm này từ bất kỳ ai, hãy yêu cầu hoàn tiền ngay lập tức!
