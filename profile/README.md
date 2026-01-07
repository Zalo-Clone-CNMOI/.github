# 📱 Zalo Clone Project  
## CNMOI_HK2_25-26_DHKTOM18CTT_CT4

Đây là GitHub Organization phục vụ cho **môn học Công Nghệ Mới (CN Mới)**  
Học kỳ: **HK2 – Năm học 2025–2026**  
Lớp: **DHKTPM18CTT_CT4**

Mục tiêu của project là xây dựng một **ứng dụng Zalo Clone** với các chức năng nhắn tin, quản lý người dùng và realtime communication, áp dụng các công nghệ mới trong phát triển phần mềm.

---

## 🎯 Mục Tiêu Dự Án

Xây dựng ứng dụng mô phỏng các chức năng cơ bản của Zalo:

- 💬 Chat 1-1 realtime
- 👥 Danh sách bạn bè
- 🔔 Thông báo tin nhắn
- 🔐 Đăng nhập / đăng ký người dùng
- 📁 Gửi hình ảnh (nâng cao)

---

## 🧱 Kiến Trúc Dự Kiến

Hệ thống được chia theo mô hình Client – Server:

### 🔧 Backend
- Node.js / NestJS
- REST API + WebSocket (Socket.IO)
- Authentication (JWT)
- PostgreSQL / MongoDB

### 🎨 Frontend
- React Native
- Giao diện chat realtime
- Quản lý state với Context / Redux

### ☁️ DevOps (nếu có)
- Docker
- Environment configuration

---

## 📦 Repositories

| Repository | Mô tả |
|--------|--------|
| `zalo-clone-backend` | Server API + WebSocket |
| `zalo-clone-frontend` | Web/Mobile Client |
| `shared` (optional) | Interface & utils dùng chung |
| `docs` | Tài liệu, báo cáo, sơ đồ |

---

## 👨‍💻 Thành Viên Nhóm

| Họ và Tên | MSSV |
|--------|--------|
| **Thình Vĩnh Phát** | 22697421 |
| **Mai Huỳnh Dương Tuấn Kiệt** | 22664321 |
| **Nguyễn Thị Yến Bình** | 22694091 |
| **Nguyễn An Nguyên** | 22669111 |
---

## 🧭 Quy Ước Làm Việc

### Branch
- `main` – bản ổn định để demo / nộp bài
- `develop` – tích hợp code
- `feature/*` – phát triển chức năng

### Commit Message
