# ระบบลงทะเบียนและประเมินความเสี่ยงสุขภาพเบื้องต้น

**Patient Health Risk Assessment and Registration System**

ระบบเว็บแอปพลิเคชันสำหรับคัดกรองผู้ป่วยเบื้องต้น คำนวณค่าดัชนีมวลกาย (BMI) และประเมินระดับความเสี่ยงด้านสุขภาพ

## 🌐 Demo

👉 [เปิดใช้งานระบบ](https://YOUR_USERNAME.github.io/BMI/)

## ✨ ฟีเจอร์

- **ตรวจสอบข้อมูล** – Validation ครบถ้วน พร้อม error message ภาษาไทย
- **คำนวณ BMI** – แสดงผลแบบ real-time พร้อม preview ก่อนกดประเมิน
- **ประเมินความเสี่ยง 3 ระดับ** – ต่ำ / ปานกลาง / สูง
- **แสดงผลสรุป** – Dialog พร้อมคำแนะนำเฉพาะบุคคล
- **MUI Components** – Container, Paper, Grid, Stack, TextField, RadioGroup, Select, Alert, Dialog, Chip

## 🛠️ เทคโนโลยี

| เทคโนโลยี | รายละเอียด |
|---|---|
| React 18 | UI Framework (CDN) |
| Material UI 5 | Component Library (CDN) |
| Babel Standalone | JSX Transform |
| Google Fonts (Sarabun) | ฟอนต์ภาษาไทย |

## 📋 การใช้งาน

1. กรอกชื่อ-นามสกุล, อายุ, น้ำหนัก, ส่วนสูง
2. เลือกพฤติกรรมการสูบบุหรี่และโรคประจำตัว
3. กดปุ่ม **ประเมินผล**
4. ดูผลการประเมินใน Dialog พร้อมคำแนะนำ

## 🚀 Deploy บน GitHub Pages

1. Push โปรเจกต์ขึ้น GitHub
2. ไปที่ **Settings → Pages**
3. เลือก Source: **Deploy from branch** → `main` → `/ (root)`
4. รอ 1–2 นาที แล้วเข้าใช้งานที่ URL ที่ได้รับ

