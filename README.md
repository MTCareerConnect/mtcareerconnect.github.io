# MT Career Connect — GitHub Pages

เว็บไซต์: https://mtcareerconnect.github.io/

## ไฟล์ในชุดนี้
| ไฟล์ | หน้าที่ |
|---|---|
| index.html | หน้าแรก |
| jobs.html | หน้าหางาน MT |
| mentors.html | หน้า Mentor ทั้งหมด |
| og-image.png | ภาพที่ขึ้นเวลาแชร์ลิงก์ (LINE / Facebook) |
| sitemap.xml, robots.txt | ให้ Google เก็บเว็บเข้าผลค้นหา |
| 404.html | ถ้าเปิดลิงก์ผิด จะพากลับหน้าแรก |
| .nojekyll | บอก GitHub ให้เสิร์ฟไฟล์ตรง ๆ |

## อัปโหลดครั้งแรก
1. สร้าง repository ชื่อ `mtcareerconnect.github.io` (Public)
2. Add file → Upload files → ลากไฟล์ทั้งหมดในโฟลเดอร์นี้ (รวม .nojekyll) → Commit changes
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. รอ 1–3 นาที แล้วเปิด https://mtcareerconnect.github.io/

## อัปเดตเว็บ
Add file → Upload files → ลากไฟล์ที่แก้ทับชื่อเดิม → Commit changes (ไม่ต้องลบไฟล์เก่าก่อน)

## ให้ Google เจอเว็บ
Google Search Console → Add property → URL prefix → https://mtcareerconnect.github.io/
→ ยืนยันด้วยไฟล์ HTML (อัปโหลดลง repo นี้) → Sitemaps → ใส่ `sitemap.xml` → Submit

## เชื่อมกับ My MTCC (รายชื่อ Mentor อัตโนมัติ)

แก้ไฟล์ `mtcc-config.js` ไฟล์เดียว: ใส่ลิงก์ Web app ของ My MTCC ใน `portal_url`

- เว้นว่าง: หน้า Mentor แสดงรายชื่อชุดเดิมในไฟล์ และปุ่มสมัครไปที่ Google Form เดิม
- ใส่แล้ว: หน้า Mentor ดึงรายชื่อจากระบบทุกครั้งที่เปิด (Mentor ที่ยินยอมและทีมอนุมัติแล้ว + โปรไฟล์แบบจำลองที่ยังไม่ได้ลบ) และปุ่มสมัครทุกปุ่มไปที่ My MTCC
