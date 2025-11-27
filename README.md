# 🎟️ Event Assistant Platform for Clubs

An all-in-one web platform designed to help college clubs manage events efficiently, while providing students with a seamless journey from event discovery to certificate download.  
The system automates **registrations, QR-based attendance, notifications, and certificate generation**.

This project is developed as part of our **Student Club Collaboration Initiative**.

---

## 👨‍💻 Team Members
- Disha N Shetty
- Pavan Hosatti
- Kirthi JC

---

## 🚀 Features

### ✔ Student Side
- Browse events across all clubs
- View event details & eligibility
- One-click registration
- Unique QR code for entry
- Certificate download after event

### ✔ Admin Side
- Create & publish events
- Track registrations and attendance
- Scan QR codes during check-in
- Bulk certificate generation
- Analytics (engagement & event stats)
- AI suggestions for event topics & timings

---

## 🛠️ Tech Stack

### 🖥️ Frontend
- **Next.js / React**
- TailwindCSS / Chakra UI
- Responsive event catalog UI

### ⚙️ Backend
- **Node.js + Express** (or Firebase Functions)
- REST APIs for event + registration + certificates

### 💾 Database
- **MongoDB Atlas / Firebase Firestore**
- Stores:
  - Users
  - Clubs
  - Events
  - Registrations
  - Attendance logs
  - Certificates

### 🖼 Media Storage
- **Cloudinary / Firebase Storage / AWS S3**
- Stores:
  - Event posters
  - QR codes
  - Certificates (PDF/Images)

### 🧠 AI Integration (Optional)
- Suggests:
  - Event topics
  - Formats (workshop, hackathon, talk, etc.)
  - Best timings (based on engagement)

---

## 📦 Tech Stack Breakdown

| Component        | Technology Used              | Why |
|-----------------|------------------------------|-----|
| Frontend        | Next.js / React              | Scalable, SPA routing, modern UI |
| Styling         | Tailwind CSS / Chakra UI     | Fast & responsive design |
| Backend API     | Node.js + Express            | Lightweight & easy to build |
| Auth            | OAuth (college email)        | Restrict access to campus users |
| Database        | MongoDB / Firestore          | Flexible for event & user data |
| QR Generation   | `qrcode` npm package         | Simple unique attendee QR |
| Certificates    | Puppeteer / pdf-lib          | HTML template → PDF automation |
| Hosting         | Vercel / Railway             | Free CI/CD & quick deployment |
| Storage/CDN     | Cloudinary / Firebase        | Fast handling of media files |



### Users
