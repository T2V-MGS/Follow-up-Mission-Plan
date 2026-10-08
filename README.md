# THEOS-2 Mission Tracker

เว็บไซต์แบบ Static สำหรับ THEOS-2 Mission Tracker (ไฟล์หลักคือ `index.html`)

## วิธีเผยแพร่ด้วย GitHub Pages
1. สร้าง GitHub repository ใหม่ (Public)
2. อัปโหลด `index.html`, `.nojekyll` และ `README.md`
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save
4. รอ 1-3 นาที จะได้ลิงก์ `https://ชื่อผู้ใช้.github.io/ชื่อrepo/`

## Netlify
ลากโฟลเดอร์นี้ไปวางที่ https://app.netlify.com/drop

## หมายเหตุ
เว็บเชื่อมต่อ Google Apps Script เพื่อซิงก์ข้อมูล หาก endpoint/token เปลี่ยน ต้องแก้ค่าในไฟล์ `index.html`
