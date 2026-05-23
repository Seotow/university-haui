# Tài liệu học tập – Đại học Công nghiệp Hà Nội (HAUI)

Repository lưu trữ toàn bộ tài liệu, bài tập và dự án từ các môn học tại HAUI, được tổ chức thành submodule theo từng năm học. Dùng làm tài liệu tham khảo cho các khóa sau.

---

## 📋 Template báo cáo

📦 **[report-template](https://github.com/Seotow/report-template)** – Template Word chuẩn HAUI dùng cho tất cả báo cáo môn học

Template `.dotx` đã cấu hình sẵn đầy đủ Style: font (Times New Roman 14pt), heading tự đánh số, hình ảnh/bảng biểu có caption tự động, mục lục và danh mục hình tự cập nhật.

```bash
git clone --recursive https://github.com/Seotow/university-haui.git
# Template nằm trong thư mục report-template/
```

---

## 📖 Hướng dẫn cho sinh viên khóa sau

### Repo này dùng để làm gì?

Đây không phải nơi copy-paste bài. Mục đích chính:
- **Tham khảo cách tổ chức project** theo từng môn, từng năm học
- **Xem cấu trúc code** của bài thực hành và đồ án để định hướng
- **Lấy template báo cáo** để viết đúng format HAUI từ đầu
- **Tra cứu kinh nghiệm** qua ARCHITECTURE.md và README từng môn

### Cài đặt nhanh

**Yêu cầu:** Git đã cài trên máy

```bash
# Clone toàn bộ (bao gồm tất cả submodule)
git clone --recursive https://github.com/Seotow/university-haui.git

# Nếu đã clone rồi mà thiếu nội dung submodule
git submodule update --init --recursive
```

> **Lưu ý:** Repo có ký hiệu 🎬 dùng **Git LFS** để lưu file lớn. Cần cài thêm:
> ```bash
> git lfs install
> git lfs pull
> ```

### Tải một môn học riêng lẻ

```bash
git clone --recursive https://github.com/Seotow/[tên-repo].git

# Ví dụ:
git clone --recursive https://github.com/Seotow/machine-learning-haui.git
```

---

## 📚 Danh sách môn học

### Năm cuối (LastYear)

| # | Môn học | Repository | Ghi chú |
|---|---------|-----------|---------|
| 1 | Lập trình Python nâng cao | [advanced-python-programming-haui](https://github.com/Seotow/advanced-python-programming-haui) | MVC, CustomTkinter, MySQL, MongoDB |
| 2 | Đồ án tốt nghiệp | [graduation-thesis-haui](https://github.com/Seotow/graduation-thesis-haui) | Nhận diện bệnh lúa – YOLOv11 + Swin Transformer |

📦 **Ứng dụng đồ án:** [plant-care](https://github.com/Seotow/plant-care) – FastAPI + Expo React Native + Docker

---

### Năm 3 (ThirdYear)

| # | Môn học | Repository | Ghi chú |
|---|---------|-----------|---------|
| 1 | Lập trình Python cơ bản | [basic-python-programming-haui](https://github.com/Seotow/basic-python-programming-haui) | |
| 2 | Phân tích dữ liệu lớn | [big-data-analysis-haui](https://github.com/Seotow/big-data-analysis-haui) | Pandas, Spark |
| 3 | Tiếng Anh 6 | [english-6-haui](https://github.com/Seotow/english-6-haui) | |
| 4 | Thực tập cơ sở ngành | [foundation-intern-haui](https://github.com/Seotow/foundation-intern-haui) | |
| 5 | Thiết kế đồ họa | [graphic-design-haui](https://github.com/Seotow/graphic-design-haui) | Photoshop, Illustrator |
| 6 | Phát triển dự án CNTT | [ict-project-dev-haui](https://github.com/Seotow/ict-project-dev-haui) | |
| 7 | Học máy | [machine-learning-haui](https://github.com/Seotow/machine-learning-haui) | TensorFlow, PyTorch |
| 8 | Đồ án chuyên ngành | [major-project-haui](https://github.com/Seotow/major-project-haui) | |
| 9 | Phát triển ứng dụng di động | [mobile-app-dev-haui](https://github.com/Seotow/mobile-app-dev-haui) | |
| 10 | Công nghệ đa phương tiện | [multimedia-technology-haui](https://github.com/Seotow/multimedia-technology-haui) | 🎬 Git LFS (563MB) |
| 11 | Quản trị mạng trên Windows | [network-admin-windows-haui](https://github.com/Seotow/network-admin-windows-haui) | 🎬 Git LFS (260MB) |
| 12 | Pháp luật đại cương | [pldc-haui](https://github.com/Seotow/pldc-haui) | |
| 13 | Tích hợp hệ thống phần mềm | [software-sys-integration-haui](https://github.com/Seotow/software-sys-integration-haui) | |
| 14 | Kiểm thử phần mềm | [software-testing-haui](https://github.com/Seotow/software-testing-haui) | |
| 15 | Tư tưởng Hồ Chí Minh | [tthcm-haui](https://github.com/Seotow/tthcm-haui) | |

**Dự án nhóm Năm 3:**
- [big-data-analytic-group17](https://github.com/Seotow/big-data-analytic-group17) – Phân tích dữ liệu lớn nhóm 17
- [TTCSN_Group16](https://github.com/Seotow/TTCSN_Group16) – Thực tập cơ sở ngành nhóm 16
- [PTDACNTT_Nhom13](https://github.com/Seotow/PTDACNTT_Nhom13) – Phát triển dự án CNTT nhóm 13
- [license-plate-recognition](https://github.com/Seotow/license-plate-recognition) – Nhận dạng biển số xe (Học máy)
- [Tiny-Fight](https://github.com/tunghuy906/Tiny-Fight) – Game (Đồ án chuyên ngành, by @tunghuy906)
- [QuanLyThuVien](https://github.com/ThAolInh20/QuanLyThuVien) – Quản lý thư viện (Phát triển ƯDDD, by @ThAolInh20)

---

### Năm 2 (SecondYear)

| # | Môn học | Repository |
|---|---------|-----------|
| 1 | Trí tuệ nhân tạo | [artificial-intelligent-haui](https://github.com/Seotow/artificial-intelligent-haui) |
| 2 | Chủ nghĩa xã hội khoa học | [cnxhkh-haui](https://github.com/Seotow/cnxhkh-haui) |
| 3 | Kiến trúc máy tính & HĐH | [computer-architecture-os-haui](https://github.com/Seotow/computer-architecture-os-haui) |
| 4 | Mạng máy tính | [computer-networks-haui](https://github.com/Seotow/computer-networks-haui) |
| 5 | Hệ quản trị cơ sở dữ liệu | [database-sys-haui](https://github.com/Seotow/database-systems-haui) |
| 6 | Cấu trúc dữ liệu & Giải thuật | [data-structs-algorithms-haui](https://github.com/Seotow/data-structures-algorithms-haui) |
| 7 | Toán rời rạc | [discrete-maths-haui](https://github.com/Seotow/discrete-mathematics-haui) |
| 8 | Tiếng Anh 3-5 | [english-3-5-haui](https://github.com/Seotow/english-3-5-haui) |
| 9 | Tương tác người máy | [human-computer-interaction-haui](https://github.com/Seotow/human-computer-interaction-haui) |
| 10 | An toàn thông tin | [information-security-haui](https://github.com/Seotow/information-security-haui) |
| 11 | Nhập môn CNPM | [intro-software-engineering-haui](https://github.com/Seotow/intro-software-engineering-haui) |
| 12 | Lịch sử Đảng CSVN | [lsdcsvn-haui](https://github.com/Seotow/lsdcsvn-haui) |
| 13 | Lập trình hướng đối tượng | [object-oriented-programming-haui](https://github.com/Seotow/object-oriented-programming-haui) |
| 14 | Xác suất thống kê | [probability-statistics-haui](https://github.com/Seotow/probability-statistics-haui) |
| 15 | Phân tích thiết kế phần mềm | [software-analysis-design-haui](https://github.com/Seotow/software-analysis-design-haui) |
| 16 | Thiết kế web | [web-design-haui](https://github.com/Seotow/web-design-haui) |

---

## 🔧 Thông tin kỹ thuật

### Quy ước đặt tên repo

```
[tên-môn-học]-haui
```

### Cập nhật submodule lên commit mới nhất

```bash
git submodule update --remote --merge
```

### Xem trạng thái tất cả submodule

```bash
git submodule status
```

---

## 📞 Liên hệ

**Nguyễn Trung Hiếu** – MSV 2022600419  
Ngành Công nghệ thông tin - Trường Công nghệ Thông tin và Truyền Thông – Đại học Công nghiệp Hà Nội  
GitHub: [@Seotow](https://github.com/Seotow) | Issues: [university-haui/issues](https://github.com/Seotow/university-haui/issues)

---

## 📝 Changelog

| Ngày | Nội dung |
|---|---|
| 2026-05-23 | Hoàn thành năm cuối: Đồ án tốt nghiệp + Python nâng cao; thêm report-template |
| 2025-07-12 | Hoàn thành tất cả 15 môn Năm 3; triển khai Git LFS; sửa cấu hình submodule |

*README được viết bởi AI*