# DebtMaster Pro 💳⚡
> แผนปลดหนี้อัจฉริยะ — AI-Powered Debt Elimination

แอพ PWA สำหรับวางแผนปลดหนี้ ใช้งานได้ทั้งบนมือถือและคอมพิวเตอร์ **ฟรี 100%**

---

## 📱 วิธีติดตั้งบนมือถือ (หลัง Deploy แล้ว)

### Android (Chrome)
1. เปิดลิงก์เว็บในมือถือ
2. กดจุด 3 จุดมุมขวาบน
3. เลือก **"Add to Home screen"**
4. กด **Add** — แอพจะปรากฏบนหน้าจอทันที

### iPhone (Safari)
1. เปิดลิงก์เว็บใน Safari
2. กดปุ่ม **Share** (กล่องมีลูกศรขึ้น)
3. เลือก **"Add to Home Screen"**
4. กด **Add**

---

## 🚀 วิธี Deploy บน GitHub Pages (ฟรี)

### ขั้นตอนที่ 1 — สร้าง GitHub Account
ไปที่ [github.com](https://github.com) แล้วสมัครสมาชิก (ฟรี)

### ขั้นตอนที่ 2 — สร้าง Repository ใหม่
1. กดปุ่ม **"+"** มุมขวาบน → **"New repository"**
2. ตั้งชื่อว่า `debtmaster-pro`
3. เลือก **Public**
4. กด **"Create repository"**

### ขั้นตอนที่ 3 — อัพโหลดไฟล์
1. คลิก **"Add file"** → **"Upload files"**
2. ลากไฟล์ทั้งหมดนี้เข้าไป:
   - `debtmaster-pro.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
3. กด **"Commit changes"**

### ขั้นตอนที่ 4 — เปิด GitHub Pages
1. ไปที่ **Settings** (แถบด้านบนของ repo)
2. เลื่อนลงหา **"Pages"** ในเมนูซ้าย
3. ใต้ **Source** เลือก **"Deploy from a branch"**
4. Branch: เลือก **main** → folder: **/ (root)**
5. กด **Save**
6. รอ 1–2 นาที แล้วจะได้ลิงก์:
   ```
   https://YOUR_USERNAME.github.io/debtmaster-pro/debtmaster-pro.html
   ```

---

## ✨ Features
- 📊 Dashboard วิเคราะห์หนี้และกระแสเงินสด
- 🧠 AI Coach แนะนำแผนปลดหนี้
- ⚡ 3 กลยุทธ์: Avalanche, Snowball, Survival
- 📈 จำลองและเปรียบเทียบผลลัพธ์
- 💾 บันทึกข้อมูลลงเครื่องอัตโนมัติ
- 📴 ใช้งานได้แม้ไม่มี Internet (Offline)

---

## 🛠 Tech Stack
- React 18 (no build step)
- Chart.js
- PWA (Service Worker + Web Manifest)
- localStorage

---

*Made with ❤️ · ฟรีตลอดชีพ ไม่มีโฆษณา ไม่เก็บข้อมูล*
