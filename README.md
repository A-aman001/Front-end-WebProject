# Buddy Nest 🐶🐱
โปรเจครายวิชา requirement และ frontend development ของกลุ่มNoname!<br>
สาขา วิศวกรรมซอฟต์แวร์ มหาวิทยาลัยพะเยา ปีการศึกษา 2567

The project for the Requirement and Frontend Development course by the Noname! Group,<br>
Software Engineering Department, University of Phayao, Academic Year 2024.


## 📌 รายละเอียดโปรเจค

เว็บไซต์ที่ให้บริการต่างๆ เกี่ยวกับสัตว์เลี้ยง เช่น บริการฝากเลี้ยงสัตว์ บริการอาบน้ำ ตัดขน กรูมมิ่ง และบริการขนส่งสัตว์เลี้ยง เพื่ออำนวยความสะดวกให้กับเจ้าของสัตว์เลี้ยง


## ✨ ฟีเจอร์หลัก
| Feature | Status |
|----------|---------|
| ระบบสมาชิก (สมัคร, เข้าสู่ระบบ, แก้ไข) | ✅ เสร็จสมบูรณ์ |
| ค้นหาและจองบริการสำหรับสัตว์เลี้ยง | ✅ เสร็จสมบูรณ์ |
| ระบบแจ้งเตือนการจอง | ✅ เสร็จสมบูรณ์ |
| รองรับการชำระเงินออนไลน์ | ✅ เสร็จสมบูรณ์ |
| รีวิวและให้คะแนนร้านค้าและบริการ | ⏳ กำลังพัฒนา|
| ระบบสำหรับแอดมิน | ⏳ กำลังพัฒนา |
| ระบบสำหรับผู้ให้บริการ(ร้านค้า) | ⏳ กำลังพัฒนา |



## 🛠 Tech Stack (Frontend)
- **Framework:** Nuxt.js (Vue 3)
- **Language:** TypeScript
- **Authentication:** sidebase/nuxt-auth, next-auth
- **UI & Styling:** TailwindCSS
- **Maps & Location:** Leaflet, Google Map
- **Security:** Cloudflare Turnstile
- **Other Libraries:**
  - Google Translate
  - Vue Advanced Cropper
  - VueQuill
  - VCalendar

## 📂 โครงสร้างโครงการ
```
buddy-nest/
│-- public/             # ไฟล์รูปภาพ ไอคอน favicon ฯลฯ
│-- src/
│   │-- components/      # คอมโพเนนต์ที่ใช้ซ้ำ
│   │-- pages/           # หน้าเว็บต่างๆ
│   │-- assets/          # ไฟล์ CSS, รูปภาพ
│   │-- utils/           # ฟังก์ชันช่วยเหลือ
│-- package.json        # รายการ dependencies
│-- README.md           # ไฟล์อธิบายโปรเจค
│-- .gitignore          # รายการไฟล์ที่ไม่ต้องการ track ใน Git
│-- nuxt.config.ts      # การตั้งค่า Nuxt.js
```

## 📖 วิธีติดตั้งและใช้งาน
```bash
# 1. Clone โปรเจค
$ git clone https://github.com/yourusername/buddy-nest.git
$ cd buddy-nest

# 2. ติดตั้ง dependencies
$ npm install

# 3. รันเซิร์ฟเวอร์
$ npm run dev
```

## 🌍 ตัวอย่างการใช้งาน (Demo)
🔗 https://front-end-web-project.vercel.app/index.html

## 👨‍💻 ทีมพัฒนา
| ชื่อ | ตำแหน่ง |
|------|----------|
| นางสาวอชิรญา เขียวกันยะ | UX/UI Developer |
| นางสาวอัมราพร อ่อนโคกสูง | UX/UI Developer |
| นางสาวหทัยชนก ตันสกุล | UX/UI Developer |
| นายอามาน อาลีแก | Frontend Developer |


## 🛠 การมีส่วนร่วม
หากต้องการพัฒนาเพิ่มเติม สามารถสร้าง Pull Request หรือ Issues ได้เลย! 😊

---

> **Buddy Nest** - เพราะสัตว์เลี้ยงของคุณคือครอบครัว 🐾
