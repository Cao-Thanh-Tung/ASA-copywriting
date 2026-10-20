# ✍️ ASA - Kho Tài Liệu & Nhật Ký Học Copywriting

Chào mừng bạn đến với kho lưu trữ nghiên cứu và thực hành **Copywriting**. Dự án này được thiết kế để lưu giữ toàn bộ kiến thức, bài tập thực hành, nhật ký làm việc và tài liệu tham khảo, giúp bạn có thể học tập liên tục trên nhiều thiết bị thông qua GitHub.

---

## 🗂️ Cấu Trúc Thư Mục

```text
ASA/
├── README.md                     # Tài liệu hướng dẫn tổng quan & đồng bộ GitHub
├── JOURNAL.md                    # Nhật ký ghi nhớ chi tiết quá trình làm việc từng buổi
├── .gitignore                    # Bộ lọc file rác khi đẩy lên Git
│
└── docs/                         # Kho tài liệu học tập
    ├── 01-nen-tang/              # Lý thuyết nền tảng, tâm lý khách hàng, insight
    │   └── tong-quan-copywriting.md
    ├── 02-cong-thuc/             # Các mô hình viết kinh điển (AIDA, PAS, FAB...)
    │   └── cac-mo-hinh-kinh-dien.md
    ├── 03-thuc-hanh/             # Bài tập thực chiến, chỉnh sửa văn phong
    │   └── bai-tap-01.md
    └── swipe-file/               # Bộ sưu tập các mẫu quảng cáo hay (Swipe File)
        └── README.md
```

---

## 🚀 Hướng Dẫn Đưa Lên GitHub & Đồng Bộ Giữa Các Máy

### Bước 1: Tạo Repository mới trên GitHub
1. Truy cập [GitHub](https://github.com) và đăng nhập vào tài khoản của bạn.
2. Nhấn nút **New** (hoặc dấu `+` ở góc trên bên phải -> **New repository**).
3. Đặt tên Repository (ví dụ: `asa-copywriting-journey` hoặc `ASA`).
4. Để chế độ **Private** (nếu muốn giữ riêng tư) hoặc **Public**.
5. **Không** tích chọn *Initialize this repository with a README* (vì thư mục máy bạn đã có sẵn).
6. Nhấn nút **Create repository**.

### Bước 2: Đẩy dự án hiện tại lên GitHub (Chạy trên máy tính này)
Mở Terminal / PowerShell tại thư mục này và chạy các lệnh sau:

```bash
# 1. Thêm link remote GitHub của bạn (thay URL bên dưới bằng link repository của bạn):
git remote add origin https://github.com/<tai-khoan-cua-ban>/<ten-repo>.git

# 2. Đổi tên nhánh sang main (nếu chưa có):
git branch -M main

# 3. Đẩy toàn bộ dữ liệu lên GitHub:
git push -u origin main
```

---

## 💻 Cách Tiếp Tục Học Ở Máy Tính Khác

Khi bạn chuyển sang máy tính khác (máy công ty, laptop, v.v.):

### 1. Lần đầu tiên lấy tài liệu về máy mới:
```bash
git clone https://github.com/<tai-khoan-cua-ban>/<ten-repo>.git
cd <ten-repo>
```

### 2. Trước mỗi buổi học (kéo tài liệu mới nhất về):
```bash
git pull origin main
```

### 3. Sau khi học xong (lưu và đẩy kết quả lên lại GitHub):
```bash
git add .
git commit -m "docs: cập nhật nhật ký buổi học ngày DD/MM/YYYY"
git push origin main
```

---

## 🧭 Lộ Trình Học Copywriting Dự Kiến

1. **Hiểu bản chất Copywriting:** Khác biệt giữa Content Writer & Copywriter, quy tắc "Một người đọc - Một thông điệp - Một hành động".
2. **Khách hàng mục tiêu & Động lực mua hàng:** Nỗi đau (Pain points), Ước mơ (Desires), Rào cản (Objections).
3. **Mô hình viết bài chuyển đổi:** AIDA, PAS, FAB, 4Ps, Hook - Story - Offer.
4. **Nghệ thuật viết Headline & Hook:** Giật tít mà không lừa dối, giữ chân người đọc trong 3 giây đầu tiên.
5. **Xây dựng Swipe File:** Thu thập và mổ xẻ những chiến dịch quảng cáo thành công.
6. **Thực chiến:** Viết bài quảng cáo Facebook/Google, Email Marketing, kịch bản Video ngắn (TikTok/Reels), Trang bán hàng (Landing Page).

> 📌 Xem chi tiết tiến độ tại file: [JOURNAL.md](file:///c:/Users/admin/Desktop/ASA/JOURNAL.md)
