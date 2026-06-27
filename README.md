# ai-brain-handbook

คู่มือสร้าง "สมอง AI" (Second Brain) ฉบับเข้าใจถึงแก่น — สร้างคลังความจำถาวรที่ AI อ่าน จดจำตัวตนของคุณ เชื่อมโยงข้อมูลเอง และพัฒนาตัวเองได้ทุกคืน

📖 อ่านออนไลน์: **https://tayakorn221.github.io/ai-brain-handbook/** (HTML ไฟล์เดียวจบ ไม่มี dependency)

## Why this exists

AI ทั่วไปลืมทุกอย่างเมื่อปิดแชต ต้องอธิบายบริบทตัวเองซ้ำทุกครั้ง คู่มือนี้เป็น single source of truth ที่ออกแบบให้กลับมาเปิดดูได้ — รวบ 6 ขั้นตอนการสร้างสมองที่สอง พร้อมเทมเพลตไฟล์และ prompt ที่ก๊อปไปใช้ได้จริง ไม่ต้องดูคลิปซ้ำ

## Quick Start

```shell
# Windows — เปิดด้วยเบราว์เซอร์เริ่มต้น
start index.html
```

ไม่ต้องติดตั้งอะไร ไม่ต้องต่อเน็ต — เปิดไฟล์เดียวจบ

## Contents

| บท | หัวข้อ |
|----|--------|
| 01 | **ภาพรวม & หลักคิด** — ปัญหา ทางออก และหลักคิด 3 ข้อ (Memory > Model) |
| 02 | **Go Pro** — ทำไมต้องอัปเกรดเป็นเวอร์ชันเสียเงิน |
| 03 | **Install the Brain** — เลือกที่เก็บถาวร (Drive / Notion / Obsidian) |
| 04 | **Give Identity** — ไฟล์ `user.md` · `soul.md` · `identity.md` พร้อมเทมเพลต |
| 05 | **Wire the Brain** — โครงสร้างโฟลเดอร์ 7+1 และการลิงก์ `[[ ]]` |
| 06 | **Feed the Brain** — สกัดข้อมูลเป็น 4 ส่วน (Decisions / Commitments / Preferences / Insights) |
| 07 | **Compound the Brain** — ลูปบำรุงรักษาข้ามคืนด้วย scheduled task |
| 08 | **Playbook** — แผนติดตั้ง 7 วัน + checklist |
| 09 | **กับดักที่พบบ่อย** — ปัญหายอดฮิตและวิธีแก้ |

## ไฟล์

| ไฟล์ | คำอธิบาย |
|------|----------|
| `index.html` | คู่มือฉบับเต็ม — single HTML, inline SVG, สารบัญ sticky, ปุ่มคัดลอกโค้ด, mobile responsive |
| `README.md` | ไฟล์นี้ — ดัชนีและจุดเริ่มต้น |

## ที่มา

แนวคิดต้นทางจากคลิป [*"This AI Brain Will Make You So Smart It's Almost Unfair"*](https://www.youtube.com/watch?v=b4d32pBa3UY) ของ Dan Martell — เรียบเรียง ขยายความ และเพิ่มเทมเพลต/diagram เป็นภาษาไทย

## เทคนิค

- HTML ไฟล์เดียวจบ ไม่มี dependency ไม่ต้องต่อเน็ต
- Inline SVG diagrams ทุกภาพ (มี `aria-label` รองรับ screen reader)
- Mobile responsive + สารบัญ sticky พร้อม active-section highlight
- ปุ่มคัดลอกโค้ด/prompt ในตัว
- ฟอนต์ใช้ system font stack ที่รองรับภาษาไทย (ไม่โหลดฟอนต์ภายนอก)

---

Last updated: 2026-06-27
