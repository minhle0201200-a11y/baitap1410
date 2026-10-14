# 🚀 SmartCampus

**SmartCampus** là ứng dụng di động giúp sinh viên PTIT *tra cứu lịch học*, xem phòng học trống và nhận thông báo mới nhất từ nhà trường.

## ✨ Tính năng đã hoàn thành

- Tra cứu lịch học theo mã sinh viên
  - Giúp sinh viên tra cứu lịch học bằng mã sinh viên.
- Xem danh sách phòng trống theo tòa nhà
  - Hỗ trợ xem các phòng đang trống theo từng tòa nhà.

## 🔗 Liên kết CLB

[Trang chủ CLB Lập trình](https://clblaptrinh.ptit.edu.vn)

![Logo SmartCampus](https://placehold.co/600x180/17365D/FFFFFF?text=SmartCampus)

> **Cảnh báo:** Dự án đang trong giai đoạn phát triển và chưa dùng cho mục đích chính thức.

---

## 🛠️ Cài đặt dự án

Chạy lần lượt các lệnh sau trong Terminal:

```bash
git clone https://github.com/clb-lap-trinh/smartcampus.git
npm install
npm start
```

## 📋 Tiến độ tính năng

- [x] Tra cứu lịch học theo mã sinh viên
- [x] Xem danh sách phòng trống theo tòa nhà
- [ ] Thông báo đẩy (push notification)
- [ ] Đăng nhập bằng tài khoản trường

## 📦 Thư viện sử dụng

| Thư viện | Phiên bản | Mục đích |
|:---|:---:|---|
| React Native | 0.74 | Xây giao diện đa nền tảng iOS/Android |
| Axios | 1.6 | Gọi API lấy dữ liệu lịch học |

## 📝 Ghi chú ôn tập

Ký tự `\*` giúp hiển thị dấu sao `*` theo nghĩa thông thường thay vì dùng nó để định dạng văn bản.

### Kiểm tra cú pháp bảng và Task List

Đoạn Markdown chưa đúng:

```markdown
| Tính năng | Trạng thái |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

-[x] Tra cứu lịch học
-[ ] Push notification
```

**Hai lỗi cú pháp:**

1. Bảng thiếu dòng phân cách giữa hàng tiêu đề và dữ liệu, ví dụ `| --- | --- |`.
2. Task List thiếu khoảng trắng sau dấu gạch ngang; cần viết `- [x]` và `- [ ]`.

Đoạn đã sửa đúng:

```markdown
| Tính năng | Trạng thái |
|---|---|
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
```
