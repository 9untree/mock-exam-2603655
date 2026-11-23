# Mock Exam 2603655 — Data Acquisition and Preparation

ข้อสอบปลายภาค **240 ข้อ** (WK8–WK15) พร้อมเฉลยและคำอธิบายทุกข้อ
สร้างเป็นเว็บไฟล์เดียว กดทำข้อสอบได้จริง ตรวจคะแนนอัตโนมัติ และใช้งาน offline ได้หลังโหลดครั้งแรก

## เปิดทำข้อสอบ

### https://9untree.github.io/mock-exam-2603655/

[![QR code](QR_GitHubPages.png)](https://9untree.github.io/mock-exam-2603655/)

## ใช้บน iPad / มือถือ

1. เปิดลิงก์ด้านบน
2. iPad: **Share → Add to Home Screen** / Android: Chrome menu → **Add to Home screen**
3. เปิดจากไอคอนที่สร้างไว้ — ใช้งานเต็มจอ และ offline ได้หลังโหลดครั้งแรก

> อย่าเปิด `index.html` จากแอป Files แล้ว tap ตรง ๆ บน iPad — Quick Look ปิด JavaScript ทำให้กดตอบไม่ได้
> ถ้าต้องใช้ไฟล์ local ให้เปิดด้วย Microsoft Edge (iPad) หรือ Chrome (Android)

## ขอบเขต

- **WK8–WK14** = 210 ข้อ (เนื้อหาออกสอบ)
- **WK15 Agentic AI** = 30 ข้อ (bonus — syllabus ระบุ “no exam”)

## โครงสร้าง

| ไฟล์ | หน้าที่ |
|---|---|
| `index.html` | ตัวเว็บทั้งหมด (ข้อสอบ + เฉลย + ระบบคะแนน) |
| `manifest.webmanifest` | ข้อมูล PWA สำหรับ Add to Home Screen |
| `sw.js` | Service worker แคชหน้าเว็บไว้ใช้ offline |
| `icon-*.png` | ไอคอนแอป |

> repo นี้เป็น public เพื่อใช้ GitHub Pages ฟรี — ไม่มีข้อมูลส่วนตัวของผู้จัดทำอยู่ในไฟล์
