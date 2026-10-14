# Ôn tập Session 08 – Bẫy cú pháp Markdown

## 1. Hai lỗi cú pháp

Đoạn ban đầu:

```markdown
| Tính năng | Trạng thái |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

-[x] Tra cứu lịch học
-[ ] Push notification
```

**Lỗi 1 – Bảng:** Thiếu hàng phân cách sau tiêu đề bảng. Cần thêm hàng có dấu gạch ngang và dấu `|`, chẳng hạn `|---|---|`.

**Lỗi 2 – Task List:** Thiếu khoảng trắng giữa dấu `-` và dấu `[` ở các mục công việc. Cần viết `- [x]` hoặc `- [ ]`.

## 2. Đoạn đã sửa

```markdown
| Tính năng | Trạng thái |
|---|---|
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
```

## 3. Kết quả mong đợi

| Tính năng | Trạng thái |
|---|---|
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification

## 4. Ghi nhớ

- Bảng Markdown cần có hàng phân cách giữa tiêu đề và dữ liệu.
- Task List cần đúng cú pháp `- [x]` cho việc hoàn thành và `- [ ]` cho việc chưa hoàn thành.
