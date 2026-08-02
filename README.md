<div align="center">

# 🎮 Block Blast — Phiên Bản Cây Nhà Lá Vườn

### Bài tập lớn: Trò chơi xếp khối (Block Puzzle) phong cách "hắc-hóa"

[![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Graphics](https://img.shields.io/badge/Graphics-SFML%203.1.0-8CC445?logo=sfml&logoColor=white)](https://www.sfml-dev.org/)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)]()
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white)]()

**Tên dự án:** Block Blast - UTC2

**Nhóm:** ⚡⚡ F5 Big Homework DSA ⚡⚡ — Lớp CQ.CNTT.K66

**Trường:** Phân hiệu Trường Đại học Giao thông vận tải TP.HCM (UTC2)

<br>

<img src="docs/images/logo.png" alt="Block Blast Logo" width="500">

</div>

---

## 📑 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Mục tiêu](#-mục-tiêu)
- [Ảnh minh họa](#-ảnh-minh-họa)
- [Thành viên và nhiệm vụ](#-thành-viên-và-nhiệm-vụ)
- [Tính năng nổi bật](#-tính-năng-nổi-bật)
- [Cài đặt & Chạy thử](#️-cài-đặt--chạy-thử)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Giấy phép](#-giấy-phép)

---

## 📖 Giới thiệu

Một trò chơi xếp khối (**block puzzle**) mang phong cách **"hắc-hóa"** đầy tính thử thách, được xây dựng bằng **C++** và thư viện đồ họa **SFML 3.1.0**. Đây không chỉ là một game xếp gạch thông thường mà còn là một bài toán tối ưu không gian lưu trữ thực tế.

## 🎯 Mục tiêu

Giúp người chơi rèn luyện tư duy logic, phản xạ nhanh nhạy, và... thử thách giới hạn chịu đựng của bản thân trước những lời "cà khịa" từ hệ thống AI của game.

---

## 🖼️ Ảnh minh họa

<div align="center">

| Menu chính | Cài đặt |
|:---:|:---:|
| ![Menu chính](docs/images/menu.png) | ![Cài đặt](docs/images/settings.png) |

| Chế độ Classic | Chế độ Time Attack |
|:---:|:---:|
| ![Chế độ Classic](docs/images/classic.png) | ![Chế độ Time Attack](docs/images/timeattack.png) |

| Chế độ Survival | Hướng dẫn chơi |
|:---:|:---:|
| ![Chế độ Survival](docs/images/survival.png) | ![Hướng dẫn chơi](docs/images/guide.png) |

| Robot "Mỏ hỗn" cà khịa | Màn hình Game Over |
|:---:|:---:|
| ![RoastBot cà khịa](docs/images/roastbot.png) | ![Game Over](docs/images/gameover.png) |

| Chọn ngôn ngữ | Lưu ý trước khi chơi |
|:---:|:---:|
| ![Chọn ngôn ngữ](docs/images/language.png) | ![Lưu ý trước khi chơi](docs/images/warning.png) |

</div>

> 📸 Ảnh trên nằm trong thư mục `docs/images/`. Muốn bổ sung ảnh mới (ví dụ pha nổ Power-up, Leaderboard...), chỉ cần thêm file `.png` vào thư mục này và chèn dòng `![Mô tả](docs/images/tên_file.png)` vào README.

---

## 👥 Thành viên và nhiệm vụ

| STT | Họ và tên | Nhiệm vụ chính |
|:---:|---|---|
| 1 | Phạm Thanh Trúc | Module Sound & Module Roast |
| 2 | Lê Đình Sơn | Module Grid & Block & Module Placement |
| 3 | Đoàn Văn Lộc | Module Score & Module Spawn |
| 4 | Huỳnh Việt Minh | Hệ thống giao diện (UI) & đa ngôn ngữ (Việt/Anh) |
| 5 | Nguyễn Phúc Minh | Logic chế độ chơi & HUD, lưu điểm |

---

## ✨ Tính năng nổi bật

### 🕹️ 3 Chế độ chơi đa dạng
- **Classic:** Lối chơi cổ điển với độ khó tăng dần (7 mốc độ khó).
- **Time Attack:** Đấu thời gian 3 phút, ăn dòng để được cộng thêm thời gian thưởng.
- **Survival:** Sinh tồn với hệ thống áp lực (Pressure) và các khối đá (Rock Blocks) cản đường.

### 💥 Khối đặc biệt (Power-ups)
Hỗ trợ các khối chức năng như Khối Bom (phá 3x3), Khối Cầu vồng (Wildcard — đặt mọi nơi), và Khối Đại bác siêu hiếm (phá 5x5).

### 🤖 Robot "Mỏ hỗn" (RoastBot)
Tích hợp một AI theo dõi nước đi. Đặt khối tệ, lỡ combo, hoặc AFK quá lâu? Robot sẽ xuất hiện và trực tiếp "cà khịa" bạn bằng Tiếng Việt hoặc Anh.

### 🎨 Đồ họa động
Bảng màu khối sinh ngẫu nhiên mỗi ván. Nền màn hình chuyển màu Gradient mượt mà từ sáng (Yên bình) sang tối (Điên rồ, Bậc thầy) dựa theo mốc điểm số.

### 🏆 Lưu trữ & Thành tựu
Lưu điểm cao riêng biệt cho 3 chế độ chơi và hỗ trợ Bảng xếp hạng (Leaderboard) cục bộ.

### 🔊 Âm thanh tổng hợp (Synth Audio)
Các hiệu ứng âm thanh (đặt khối, ăn combo, vãng game) được lập trình tổng hợp trực tiếp bằng sóng Sine tạo độ "tưng" rất đã tai, tích hợp sẵn không cần file nhạc ngoài.

---

## ⚙️ Cài đặt & Chạy thử

```bash
# Bước 1: Tải file BlockBlast_Team10_UTC2.7z đã nén được gửi trên GitHub Releases
# Bước 2: Giải nén file vừa tải — Bước này rất quan trọng!
# Bước 3: Bấm vào file vừa giải nén, tìm tệp .exe và chạy
# Bước 4: Màn hình game hiển thị và giải trí thôi nào! 🎉
```

> ⚠️ **Lưu ý:** Đảm bảo đã giải nén toàn bộ file trước khi chạy `.exe`, nếu không game sẽ báo lỗi thiếu tài nguyên (assets/dll).

### Yêu cầu hệ thống
- Hệ điều hành: Windows 10/11
- Thư viện: SFML 3.1.0 (đã đóng gói kèm bản build)

### Build từ source (dành cho developer)

```bash
git clone https://github.com/<tên-repo-cua-nhom>/BlockBlast-UTC2.git
cd BlockBlast-UTC2
mkdir build && cd build
cmake ..
cmake --build . --config Release
```

---

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ:** C++
- **Thư viện đồ họa:** [SFML 3.1.0](https://www.sfml-dev.org/)
- **Công cụ build:** CMake
- **Quản lý phiên bản:** Git & GitHub

---

## 📄 Giấy phép

Dự án được phát hành theo giấy phép [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ và không ít lần bị RoastBot "cà khịa" bởi **Nhóm F5 Big Homework DSA**

</div>

