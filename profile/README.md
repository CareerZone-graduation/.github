<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=220&section=header&text=CareerZone&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Nền%20tảng%20tuyển%20dụng%20thông%20minh%20thế%20hệ%20mới&descSize=20&descAlignY=60&descColor=E0E7FF" alt="CareerZone Banner" width="100%"/>

<br/>

[![GitHub Org](https://img.shields.io/badge/GitHub-CareerZone--graduation-4F46E5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CareerZone-graduation)
[![License](https://img.shields.io/badge/License-MIT-7C3AED?style=for-the-badge)](LICENSE)
[![Made with React](https://img.shields.io/badge/React-v19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![Node.js](https://img.shields.io/badge/Node.js-v18+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)

<br/>

> **CareerZone** là nền tảng tuyển dụng toàn diện kết nối **ứng viên** và **nhà tuyển dụng** với trải nghiệm hiện đại, tính năng real-time và công cụ AI hỗ trợ xây dựng sự nghiệp.

</div>

---

## 🌟 Giới Thiệu

CareerZone được xây dựng như một **đồ án tốt nghiệp** với kiến trúc ứng dụng thực tế, gồm 4 module chính liên kết chặt chẽ với nhau — từ giao diện ứng viên, cổng thông tin nhà tuyển dụng, bảng điều khiển quản trị đến backend API mạnh mẽ.

```
┌─────────────────────────────────────────────────────────────────┐
│                        CareerZone Platform                      │
├─────────────────┬─────────────────┬──────────────────────────── │
│   CZCandidate   │   CZEmployer    │        CZAdmin              │
│  (Ứng viên)     │ (Nhà tuyển dụng)│     (Quản trị viên)        │
│  Port :3000     │  Port :4000     │       Port :3200            │
└────────┬────────┴────────┬────────┴────────────┬────────────────┘
         │                 │                      │
         └─────────────────┴──────────────────────┘
                                 │
                    ┌────────────▼────────────┐
                    │       CZBackend         │
                    │   REST API + Socket.io  │
                    │       Port :5000        │
                    └─────────────────────────┘
                           │            │
                    ┌──────▼──┐  ┌──────▼──────┐
                    │ MongoDB │  │    Redis     │
                    └─────────┘  └─────────────┘
```

---

## 📦 Repositories

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Mô tả</th>
      <th>Công nghệ</th>
      <th>Demo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/CareerZone-graduation/CZCandidate">
          <img src="https://img.shields.io/badge/🎯_CZCandidate-4F46E5?style=flat-square&logoColor=white" alt="CZCandidate"/>
        </a>
      </td>
      <td>Ứng dụng dành cho ứng viên tìm kiếm việc làm, xây dựng CV và theo dõi đơn ứng tuyển</td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
      </td>
      <td><a href="https://career-zone-candidate-fe-delta.vercel.app/">🔗 Live</a></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/CareerZone-graduation/CZEmployer">
          <img src="https://img.shields.io/badge/🏢_CZEmployer-7C3AED?style=flat-square&logoColor=white" alt="CZEmployer"/>
        </a>
      </td>
      <td>Cổng thông tin nhà tuyển dụng — đăng tin, quản lý ứng viên, lên lịch phỏng vấn</td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white"/>
      </td>
      <td><em>Coming soon</em></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/CareerZone-graduation/CZAdmin">
          <img src="https://img.shields.io/badge/⚙️_CZAdmin-059669?style=flat-square&logoColor=white" alt="CZAdmin"/>
        </a>
      </td>
      <td>Bảng điều khiển quản trị — quản lý người dùng, công ty, tin tuyển dụng và giao dịch</td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Recharts-FF6B6B?style=flat-square"/>
        <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white"/>
      </td>
      <td><a href="https://career-zone-admin-fe.vercel.app/">🔗 Live</a></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/CareerZone-graduation/CZBackend">
          <img src="https://img.shields.io/badge/🔧_CZBackend-DC2626?style=flat-square&logoColor=white" alt="CZBackend"/>
        </a>
      </td>
      <td>REST API backend phục vụ toàn bộ hệ thống với real-time, queue jobs và xác thực bảo mật</td>
      <td>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      </td>
      <td><em>API Server</em></td>
    </tr>
  </tbody>
</table>

---

## ✨ Tính Năng Nổi Bật

<table>
  <tr>
    <td width="50%">

### 🎯 Dành cho Ứng viên
- **Tìm kiếm nâng cao** với bộ lọc đa chiều (ngành nghề, mức lương, kinh nghiệm, vị trí địa lý)
- **Bản đồ tương tác** tìm kiếm việc làm theo địa điểm với Leaflet
- **CV Builder** kéo thả, nhiều mẫu chuyên nghiệp, xuất PDF
- **Gợi ý việc làm** phù hợp dựa trên kỹ năng hồ sơ
- **Theo dõi ứng tuyển** real-time và chat với nhà tuyển dụng
- **Thông báo push** qua Firebase & Socket.io

    </td>
    <td width="50%">

### 🏢 Dành cho Nhà tuyển dụng
- **Dashboard thống kê** — phân tích hiệu quả tuyển dụng
- **Quản lý tin tuyển dụng** đầy đủ vòng đời (nháp → duyệt → đang tuyển)
- **Sàng lọc ứng viên** thông minh, shortlist và đánh giá
- **Lên lịch phỏng vấn** tích hợp email mời tự động
- **Phỏng vấn video** trực tuyến
- **Gói dịch vụ & thanh toán** linh hoạt

    </td>
  </tr>
  <tr>
    <td width="50%">

### ⚙️ Dành cho Quản trị viên
- **Tổng quan hệ thống** — users, jobs, companies, revenue
- **Duyệt công ty** và xác minh thông tin
- **Kiểm duyệt tin tuyển dụng** với quản lý tin nổi bật
- **Báo cáo doanh thu** và xuất báo cáo giao dịch

    </td>
    <td width="50%">

### 🔧 Backend & Infrastructure
- **RESTful API** với Express.js v5 phân quyền theo vai trò
- **Real-time** với Socket.io (chat, thông báo)
- **Background Jobs** xử lý email, PDF, nhắc nhở phỏng vấn qua RabbitMQ
- **Xác thực** JWT + Passport.js + OAuth Google
- **File Storage** Cloudinary & AWS S3
- **Vector Embedding** gợi ý việc làm thông minh

    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Frontend
![React](https://img.shields.io/badge/React_v19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_v7-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6B6B?style=for-the-badge)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js_v18+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_v5-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

</div>

---

## 🏗️ Kiến Trúc Hệ Thống

```
                              CareerZone Architecture
═══════════════════════════════════════════════════════════════════
  CLIENTS
  ┌──────────────────┐  ┌──────────────────┐  ┌──────────────────┐
  │   CZCandidate    │  │   CZEmployer     │  │    CZAdmin       │
  │  React + Vite    │  │  React + Vite    │  │  React + Vite    │
  │  TanStack Query  │  │  Redux Toolkit   │  │  Redux Toolkit   │
  │  Framer Motion   │  │  shadcn/ui       │  │  Recharts        │
  └────────┬─────────┘  └────────┬─────────┘  └────────┬─────────┘
           │                     │                      │
═══════════╪═════════════════════╪══════════════════════╪══════════
  GATEWAY  │                     │                      │
           └─────────────────────┴──────────────────────┘
                                 │ HTTPS / WSS
                    ┌────────────▼────────────┐
                    │       CZBackend         │
                    │  Express.js v5 REST API │
                    │  ┌───────────────────┐  │
                    │  │   Middleware      │  │
                    │  │  JWT Auth + RBAC  │  │
                    │  │  Rate Limiting    │  │
                    │  │  Zod Validation   │  │
                    │  └───────────────────┘  │
                    │  ┌───────────────────┐  │
                    │  │  Socket.io Server │  │
                    │  │  Real-time Chat   │  │
                    │  │  Notifications    │  │
                    │  └───────────────────┘  │
                    │  ┌───────────────────┐  │
                    │  │  Background Jobs  │  │
                    │  │  RabbitMQ Workers │  │
                    │  │  Email / PDF / AI │  │
                    │  └───────────────────┘  │
                    └───────────┬─────────────┘
                                │
           ┌────────────────────┼────────────────────┐
           │                    │                    │
  ┌────────▼────────┐  ┌────────▼────────┐  ┌───────▼──────────┐
  │    MongoDB      │  │     Redis       │  │   External APIs  │
  │  (Primary DB)   │  │  (Cache/Queue)  │  │  Google OAuth    │
  │  Mongoose ODM   │  │  Session Store  │  │  Firebase FCM    │
  └─────────────────┘  └─────────────────┘  │  Cloudinary / S3 │
                                             │  Goong Maps      │
                                             └──────────────────┘
```

---

## 👥 Đội Ngũ Phát Triển

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/tuoitho">
          <img src="https://github.com/tuoitho.png" width="100px" style="border-radius:50%" alt="tuoitho"/>
          <br/>
          <sub><b>Lê Đình Trí</b></sub>
        </a>
        <br/>
        <a href="https://github.com/tuoitho">
          <img src="https://img.shields.io/badge/@tuoitho-4F46E5?style=flat-square&logo=github&logoColor=white"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/iamtien-cmd">
          <img src="https://github.com/iamtien-cmd.png" width="100px" style="border-radius:50%" alt="iamtien-cmd"/>
          <br/>
          <sub><b>TienLien</b></sub>
        </a>
        <br/>
        <a href="https://github.com/iamtien-cmd">
          <img src="https://img.shields.io/badge/@iamtien--cmd-7C3AED?style=flat-square&logo=github&logoColor=white"/>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 🚀 Bắt Đầu Nhanh

```bash
# 1. Clone backend
git clone https://github.com/CareerZone-graduation/CZBackend.git
cd CZBackend && pnpm install && pnpm run dev   # :5000

# 2. Clone ứng dụng ứng viên
git clone https://github.com/CareerZone-graduation/CZCandidate.git
cd CZCandidate && pnpm install && pnpm run dev  # :3000

# 3. Clone cổng thông tin nhà tuyển dụng
git clone https://github.com/CareerZone-graduation/CZEmployer.git
cd CZEmployer && pnpm install && pnpm run dev   # :4000

# 4. Clone bảng điều khiển quản trị
git clone https://github.com/CareerZone-graduation/CZAdmin.git
cd CZAdmin && pnpm install && pnpm run dev      # :3200
```

> **Yêu cầu:** Node.js ≥ 18, pnpm, MongoDB, Redis

---

## 📄 License

Tất cả các repository trong tổ chức này được phân phối dưới [MIT License](https://opensource.org/licenses/MIT).

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=100&section=footer" alt="footer" width="100%"/>

**CareerZone** — Xây dựng bởi ❤️ như một đồ án tốt nghiệp

[![GitHub Org](https://img.shields.io/badge/Xem_tất_cả_repositories-4F46E5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CareerZone-graduation)

</div>
