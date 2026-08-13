# เว็บไซต์เรียนรู้ชุมชนภาคใต้ — ชุดสุดท้ายพร้อมเผยแพร่

ไฟล์เว็บไซต์แบบ Static HTML/CSS/JavaScript พร้อมสำหรับ GitHub Pages หรือโฮสต์ Static Site อื่น ๆ

## ไฟล์หลัก
- `index.html` — หน้าเว็บไซต์
- `assets/background.png` — ภาพพื้นหลังภูเขา ชุมชน และการประกอบอาชีพภาคใต้
- `assets/learning-video.mp4` — คลิป “ปาฏิหาริย์ชุมพรและแก้มลิง”
- `.nojekyll` — ใช้สำหรับการเผยแพร่แบบ static โดยไม่ต้องผ่าน Jekyll

## เผยแพร่ด้วย GitHub Pages
1. สร้าง Repository ใหม่บน GitHub
2. อัปโหลด `index.html`, โฟลเดอร์ `assets` และ `.nojekyll` ไปไว้ที่ระดับบนสุดของ Repository
3. ไปที่ **Settings → Pages**
4. เลือก **Deploy from a branch**
5. เลือก branch `main` และโฟลเดอร์ `/ (root)` แล้วกด Save
6. รอให้ GitHub Pages เผยแพร่เว็บไซต์ แล้วเปิด URL ที่ GitHub แสดง

เว็บไซต์นี้ไม่ต้องใช้ฐานข้อมูลหรือเซิร์ฟเวอร์ Node.js และใช้ localStorage สำหรับคะแนน/เหรียญในเบราว์เซอร์ของผู้เรียน

## หมายเหตุเรื่องเกม
Nongyai Runner 3D ใช้ลิงก์ Gemini ภายนอก จึงเปิดในแท็บใหม่แทนการฝัง iframe เพื่อหลีกเลี่ยงปัญหา “ปฏิเสธการเชื่อมต่อ”
