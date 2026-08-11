77 STAR - ระบบพนักงาน / ผู้จัดการ
1. วาง index.html, config.js, schema.sql ไว้ในโฟลเดอร์เดียวกัน
2. รัน schema.sql ใน Supabase SQL Editor
3. ใส่ Supabase URL และ Publishable Key ใน config.js
4. เปิดด้วย localhost (แนะนำ python -m http.server 8000)
5. หน้าแรกจะไม่มี Login ตามที่ขอ และมีปุ่ม "พนักงาน" / "ผู้จัดการ"
หมายเหตุ: เพราะไม่มีระบบ Login จริง การเลือกบทบาทเป็นการแยกหน้าการใช้งาน ไม่ใช่การรักษาความปลอดภัยแบบบัญชีผู้ใช้
