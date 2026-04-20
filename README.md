# Hi, I'm Minh Khoa 👋
Backend Developer focused on **ASP.NET Core** and **REST API development**.

---

## 🚀 Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

## 🚀 Featured Project

**TradeHub**  
P2P marketplace backend API built with ASP.NET Core.

Key features:

- JWT authentication  
- Product listing and order management  
- Transaction handling  

---

## 🎯 Current Focus

- Building scalable backend services with ASP.NET Core  
- Improving API design and backend architecture


## 📁 Project Structure

```text
├── docker-compose.yml       # Cấu hình Docker để khởi chạy các services cùng lúc (DB, Client, Server)
├── README.md                # Tệp tài liệu chính tóm tắt về dự án
├── nginx/                   # Chứa cấu hình cho Nginx (Reverse Proxy/Load Balancer)
├── src/                     # Trọng tâm của mã nguồn
│   │
│   ├── client/              # NƠI CHỨA MÃ NGUỒN FRONTEND (Web App)
│   │   ├── src/
│   │   │   ├── components/  # Các React components có thể tái sử dụng (Button, Modal, ChatBubble...)
│   │   │   ├── contexts/    # Quản lý state toàn cục với React Context (AuthContext...)
│   │   │   ├── hooks/       # Custom React Hooks sử dụng cho logic chung
│   │   │   ├── pages/       # Các trang giao diện chính (Login, ChatWindow, Cài đặt...)
│   │   │   ├── services/    # Logic thực hiện gọi API backend (Axios) và WebSocket
│   │   │   └── App.tsx      # Entrypoint chính cho React Component Tree và Routing
│   │   └── package.json     # Chứa danh sách các thư viện của Frontend
│   │
│   └── server/              # NƠI CHỨA MÃ NGUỒN BACKEND (Node.js/Express)
│       ├── app.js           # Tệp khởi chạy chính của Express Server
│       ├── configs/         # Các biến cấu hình (Database, biến môi trường)
│       ├── middlewares/     # Middleware xử lý Request trước khi vào Controller (Auth, Error, Upload)
│       ├── models/          # Các Model Schema tương tác với MongoDB (User, Message, Call...)
│       ├── socket/          # Thư mục xử lý kết nối và sự kiện thời gian thực (Socket.io)
│       ├── modules/         # Chứa API Controllers & Routes theo mô hình Modular
│       │   ├── auth/        # Xử lý Đăng ký / Đăng nhập / Token
│       │   ├── calls/       # Xử lý báo hiệu cuộc gọi Audio / Video
│       │   ├── chat/        # Xử lý tác vụ gửi, nhận và lấy dữ liệu tin nhắn
│       │   ├── groups/      # Quản lý tạo nhóm, thêm mem
│       │   └── users/       # Quản lý hồ sơ người dùng, kết bạn
│       └── package.json     # Chứa danh sách các thư viện của Backend
```
