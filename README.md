# Red Lily — Time-based Celestial Engine

เว็บจำลองการเติบโตของดอกลิลลี่สีแดง พร้อมท้องฟ้าที่เปลี่ยนตามเวลาจริงของประเทศไทย (GMT+7) สร้างด้วย HTML, CSS และ JavaScript Canvas

## ทดลองใช้งานในเครื่อง

เปิดไฟล์ `index.html` ด้วยเว็บเบราว์เซอร์สมัยใหม่ได้โดยตรง ไม่ต้องติดตั้ง Node.js หรือ Backend

## คุณสมบัติ

- ติดตามเวลาประเทศไทย (GMT+7) แบบ Real-time พร้อมแสดงชั่วโมง นาที และวินาที
- ท้องฟ้าเปลี่ยนโทนสีและตำแหน่งดวงอาทิตย์/ดวงจันทร์ตามเวลาจริง
- แอนิเมชันการเติบโตของลำต้น ใบ กลีบดอก เกสร และอนุภาค
- ปุ่ม Pause / Play สำหรับหยุดและเล่นแอนิเมชัน
- ปุ่ม Reset เพื่อเริ่มลำดับการเติบโตใหม่

## คีย์บอร์ด

- `Space` — หยุด/เล่นแอนิเมชัน
- `R` — เริ่มลำดับการเติบโตใหม่

## เผยแพร่ด้วย GitHub Pages

Repository นี้มี GitHub Actions workflow ที่ `.github/workflows/pages.yml` เมื่อเปิดใช้ Pages โดยเลือก **GitHub Actions** เป็น Build and deployment source แล้ว push ไปยัง `main` (หรือกด Run workflow) ระบบจะเผยแพร่เว็บให้อัตโนมัติ

หน้าเว็บของ repository นี้จะอยู่ที่:

https://lucuss00.github.io/Red-Lily-Time-based-Celestial-Engine/

> หมายเหตุ: หากเป็นการ Deploy ครั้งแรก ให้เข้า Settings → Pages แล้วตั้ง Source เป็น **GitHub Actions** ก่อน
