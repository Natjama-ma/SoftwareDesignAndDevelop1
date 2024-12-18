# บันทึกการยอมรับระบบ
# (Acceptance Record)

| หัวข้อ | รายละเอียด |
|-------|------------|
| รหัสเอกสาร | ACC-HOTEL-2024-001 |
| เวอร์ชัน | 1.0 |
| โครงการ | ระบบจองห้องพักออนไลน์ |
| วันที่ทดสอบ | 1-3 ธันวาคม 2024 |
| สถานที่ทดสอบ | ห้องประชุม IT Training Center |

## 1. รายละเอียดการทดสอบ

### 1.1 ผู้เข้าร่วมการทดสอบ

| ชื่อ | ตำแหน่ง | บทบาท | หน่วยงาน |
|-----|---------|--------|-----------|
| นางสาว สมหญิง ใจดี | Front Office Manager | ผู้ใช้งานหลัก | ฝ่ายต้อนรับ |
| นาย สมชาย รักงาน | Project Manager | ผู้ดูแลโครงการ | IT |
| นาย สมศักดิ์ เก่งกล้า | Technical Lead | ผู้พัฒนาระบบ | IT |
| นาง สมใจ พิถีพิถัน | QA Manager | ผู้ทดสอบระบบ | QA |

### 1.2 ขอบเขตการทดสอบ

| โมดูล | ฟังก์ชันที่ทดสอบ | ผู้ทดสอบ |
|-------|------------------|-----------|
| ระบบจองห้องพัก | - การค้นหาห้อง<br>- การจองห้อง<br>- การยกเลิกจอง | สมหญิง |
| ระบบชำระเงิน | - ชำระผ่านบัตร<br>- โอนเงิน<br>- คืนเงิน | สมหญิง |
| ระบบจัดการ | - จัดการห้องพัก<br>- จัดการราคา<br>- จัดการโปรโมชั่น | สมใจ |
| รายงาน | - รายงานการจอง<br>- รายงานรายได้<br>- รายงานสถิติ | สมใจ |

## 2. ผลการทดสอบ

### 2.1 สรุปผลการทดสอบตามเกณฑ์การยอมรับ

| เกณฑ์การยอมรับ | ผลการทดสอบ | สถานะ | หมายเหตุ |
|----------------|--------------|--------|-----------|
| ระบบทำงานถูกต้องตาม Requirements | ผ่าน 95% | ผ่าน | มีข้อแก้ไขเล็กน้อย |
| Response Time < 3 วินาที | 2.5 วินาที | ผ่าน | - |
| รองรับผู้ใช้พร้อมกัน 100 คน | 120 คน | ผ่าน | - |
| ความปลอดภัยตามมาตรฐาน | ผ่านการทดสอบ | ผ่าน | - |
| Data Accuracy 100% | 100% | ผ่าน | - |

### 2.2 รายการข้อบกพร่องที่พบ

| รหัส | รายละเอียด | ระดับ | สถานะ | กำหนดแก้ไข |
|------|------------|--------|--------|-------------|
| D001 | การแสดงผลรายงานช้า | ต่ำ | แก้ไขแล้ว | 4 ธ.ค. 24 |
| D002 | ข้อความแจ้งเตือนไม่ชัดเจน | ต่ำ | แก้ไขแล้ว | 4 ธ.ค. 24 |
| D003 | พิมพ์ใบเสร็จไม่ถูกต้อง | ปานกลาง | กำลังแก้ไข | 5 ธ.ค. 24 |

## 3. ข้อเสนอแนะจากผู้ใช้งาน

| ลำดับ | ข้อเสนอแนะ | ระดับความสำคัญ | การดำเนินการ |
|-------|------------|----------------|---------------|
| 1 | ควรเพิ่มการแจ้งเตือนผ่าน Line | ต่ำ | Phase 2 |
| 2 | ต้องการ Export รายงานเป็น Excel | ปานกลาง | จะดำเนินการ |
| 3 | ต้องการดูประวัติการจองย้อนหลัง | ต่ำ | Phase 2 |

## 4. การยอมรับระบบ

### 4.1 เงื่อนไขการยอมรับ
- [x] ระบบทำงานได้ตามความต้องการหลัก
- [x] ไม่พบข้อผิดพลาดร้ายแรง
- [x] ผู้ใช้งานสามารถใช้งานระบบได้
- [x] เอกสารประกอบครบถ้วน

### 4.2 เอกสารที่ส่งมอบ
1. คู่มือการใช้งานระบบ
2. คู่มือการดูแลระบบ
3. เอกสารการออกแบบระบบ
4. แผนการบำรุงรักษา
5. รายงานผลการทดสอบ

### 4.3 การรับประกันและสนับสนุน
- ระยะเวลารับประกัน: 1 ปี
- การสนับสนุน: 24/7
- SLA: ตอบสนองภายใน 2 ชั่วโมง

## 5. การลงนามยอมรับระบบ

ผู้ใช้งาน:
| ชื่อ | ตำแหน่ง | ลายเซ็น | วันที่ |
|-----|---------|----------|--------|
| นางสาว สมหญิง ใจดี | Front Office Manager | _________ | _______ |

ผู้บริหาร:
| ชื่อ | ตำแหน่ง | ลายเซ็น | วันที่ |
|-----|---------|----------|--------|
| นาย สมบัติ ผู้จัดการ | Hotel Manager | _________ | _______ |

ทีมพัฒนา:
| ชื่อ | ตำแหน่ง | ลายเซ็น | วันที่ |
|-----|---------|----------|--------|
| นาย สมชาย รักงาน | Project Manager | _________ | _______ |
| นาย สมศักดิ์ เก่งกล้า | Technical Lead | _________ | _______ |

## 6. หมายเหตุ
1. ระบบได้รับการยอมรับและพร้อมใช้งานจริง
2. ข้อเสนอแนะจะได้รับการพิจารณาในการพัฒนา Phase ถัดไป
3. การแก้ไขข้อบกพร่องที่เหลือจะดำเนินการให้แล้วเสร็จภายใน 5 ธ.ค. 2024
