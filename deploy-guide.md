# วิธี Deploy Dashboard บน GitHub Pages
## ทำครั้งเดียว ใช้ได้ตลอด

---

## ขั้นตอนที่ 1 — สมัคร GitHub (5 นาที)

1. ไปที่ https://github.com
2. กด **Sign up** มุมขวาบน
3. กรอก: Email · Password · Username (เช่น `chamchuri-utd`)
4. เลือก plan: **Free** → Continue
5. ยืนยัน email ที่ได้รับ

---

## ขั้นตอนที่ 2 — สร้าง Repository (2 นาที)

1. กด **+** มุมขวาบน → **New repository**
2. ตั้งชื่อ: `chamchuri-dashboard`  
   ⚠️ ชื่อ repo จะกลายเป็นส่วนหนึ่งของ URL
3. ตั้งเป็น **Public** (ต้อง Public ถึงจะใช้ Pages ฟรีได้)
4. ✅ เช็ก **Add a README file**
5. กด **Create repository**

---

## ขั้นตอนที่ 3 — Upload ไฟล์ index.html (2 นาที)

1. ใน repo ที่เพิ่งสร้าง กด **Add file** → **Upload files**
2. ลาก `index.html` วางในกรอบ
3. เลื่อนลงมา กด **Commit changes**

---

## ขั้นตอนที่ 4 — เปิด GitHub Pages (1 นาที)

1. กดแท็บ **Settings** (ใน repo)
2. เมนูซ้าย → **Pages**
3. ใต้ **Source** เลือก:
   - Branch: `main`
   - Folder: `/ (root)`
4. กด **Save**

รอ 1-2 นาที แล้วจะเห็น URL:  
`https://[username].github.io/chamchuri-dashboard/`

---

## ขั้นตอนที่ 5 — แชร์ให้ทีม

คัดลอก URL ด้านบนส่งให้ทีมได้เลย  
เปิดบน mobile / desktop ได้ทุก browser ไม่ต้อง login

---

## อัพเดตข้อมูลในอนาคต

ทุกครั้งที่มีข้อมูลใหม่:
1. ส่ง Excel ไฟล์ใหม่มาให้ Claude
2. Claude จะสร้าง `index.html` ใหม่พร้อมข้อมูลล่าสุด
3. ไปที่ repo → **Add file** → **Upload files**
4. ลาก `index.html` ใหม่ทับของเดิม → **Commit changes**
5. รอ 1 นาที → URL เดิมจะอัพเดตอัตโนมัติ

---

## URL สุดท้ายของคุณ

```
https://[username].github.io/chamchuri-dashboard/
```

แทน `[username]` ด้วย GitHub username ที่สมัคร
