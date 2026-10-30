# Red Lily — Time-based Celestial Engine

เว็บจำลองการเติบโตของดอกลิลลี่สีแดง พร้อมท้องฟ้าที่เปลี่ยนตามเวลาจำลองของประเทศไทย (GMT+7) สร้างด้วย HTML, CSS และ JavaScript Canvas

## ทดลองใช้งานในเครื่อง

เปิดไฟล์ `index.html` ด้วยเว็บเบราว์เซอร์สมัยใหม่ได้โดยตรง ไม่ต้องติดตั้ง Node.js หรือ Backend

## การควบคุม

- **ตั้งเวลา** — ป้อนเวลา เช่น `14:30` หรือเลือกเวลาสำเร็จรูป
- **เวลาจริง** — ใช้เวลาประเทศไทย ณ ขณะนั้น
- **⏸ / ▶** — หยุดหรือเล่นแอนิเมชันต่อ
- **🔄** — เริ่มแอนิเมชันการเติบโตใหม่
- **-1 ชม. / -15 นาที / +15 นาที / +1 ชม.** — ปรับเวลาท้องฟ้า

คีย์บอร์ด: `T` เปิดหน้าตั้งเวลา, `Space` หยุด/เล่น, `R` เริ่มใหม่, ลูกศรซ้าย/ขวาปรับ 15 นาที และลูกศรขึ้น/ลงปรับ 1 ชั่วโมง

## เผยแพร่ด้วย GitHub Pages

Repository นี้มี GitHub Actions workflow ที่ `.github/workflows/pages.yml` แล้ว เมื่อเปิดใช้ Pages โดยเลือก **GitHub Actions** เป็น Build and deployment source แล้ว push ไปยัง `main` (หรือกด Run workflow) ระบบจะเผยแพร่เว็บให้อัตโนมัติ

หน้าเว็บของ repository นี้จะอยู่ที่:

https://lucuss00.github.io/Red-Lily-Time-based-Celestial-Engine/

> หมายเหตุ: การ Deploy ครั้งแรกอาจต้องเข้า Settings → Pages แล้วตั้ง Source เป็น **GitHub Actions** ก่อน
