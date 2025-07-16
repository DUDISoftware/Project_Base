# 🌱 MERN Base Project - Admin & User Roles (Vite + Tailwind)

Một project base hiện đại sử dụng **MERN stack** (MongoDB, Express, React, Node.js) kết hợp với **Vite** và **TailwindCSS**, có cấu trúc chuẩn và sẵn sàng mở rộng.  
Phù hợp cho các hệ thống web như: quản trị người dùng, đặt lịch dịch vụ, e-commerce, dashboard,...

---

## 📂 Cấu trúc dự án

Project_Base_MERN/
├── be/ # Backend: Express + MongoDB
├── fe/ # Frontend: React + Vite + Tailwind
│ ├── layouts/ # AdminLayout, MainLayout, AuthLayout
│ ├── views/
│ │ ├── admin/ # Giao diện admin
│ │ ├── user/ # Giao diện người dùng
│ │ └── auth/ # Đăng nhập / Đăng ký
│ ├── routes/ # AppRoutes.jsx - cấu hình route theo layout
│ ├── services/ # Axios service
│ ├── context/ # AuthContext
│ └── hooks/ # Custom hook (useAuth,...)


---

## 🚀 Tech Stack

- **Frontend:**
  - [React.js](https://reactjs.org/)
  - [Vite](https://vitejs.dev/)
  - [TailwindCSS](https://tailwindcss.com/)
  - React Router v6
  - Axios

- **Backend:**
  - Express.js
  - MongoDB + Mongoose
  - JWT Authentication
  - dotenv, bcryptjs, cors, etc.

---

## 🧠 Tính năng nổi bật

✅ Giao diện tách biệt: User / Admin  
✅ Layouts quản lý rõ ràng  
✅ Auth login/register (JWT)  
✅ React Context API lưu trạng thái đăng nhập  
✅ Routing phân quyền (Private + Role-based)  
✅ Axios cấu hình baseURL  
✅ TailwindCSS cho giao diện responsive  
✅ Cấu trúc dễ mở rộng & tái sử dụng

---

## 🛠️ Cài đặt

### 1. Clone project

```bash
git clone https://github.com/DUDISoftware/Project_Base

