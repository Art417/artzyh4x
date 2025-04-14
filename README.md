# ระบบเปิดซุ้มการ์ดสุ่มไอเท็ม (Gacha Card System)

![Gacha Card Preview](assets/preview.gif)

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge)](https://your-demo-link.com)
[![GitHub Followers](https://img.shields.io/github/followers/artzyh4x?label=GitHub&style=social)](https://github.com/artzyh4x)

---

โปรเจกต์นี้เป็นระบบสุ่มกาชาแบบ "เปิดซุ้มการ์ดทีละใบ" ที่ให้ความรู้สึกเหมือนเปิดการ์ดในเกมจริง ๆ ทั้งภาพ เสียง และเอฟเฟกต์ต่าง ๆ  
เหมาะสำหรับเว็บเกมหรือการต่อยอดในโปรเจกต์ FiveM หรือเกมแนว RPG

## ฟีเจอร์

- เปิดซุ้มการ์ดสุ่มไอเท็มพร้อมภาพและเสียง
- ระบบสุ่มไอเท็มตามระดับความหายาก (Rarity)
- สามารถปรับแต่งไอเท็มและระดับความหายากได้ตามใจ
- โค้ดเขียนด้วย HTML, CSS และ JavaScript แบบง่าย ๆ เพื่อความต่อยอด

## ระดับความหายากของไอเท็ม

- **Standard**  
- **Heroic**  
- **Epic**  
- **Limited**  
- **Legend**  
- **Ultimate**  
- **Mythical** *(หายากสุด ได้จากกิจกรรมพิเศษเท่านั้น)*

## รายการไอเท็มตัวอย่าง

```json
[
  {"name": "ปากฉลาม I", "rarity": "Standard"},
  {"name": "ปากฉลาม II", "rarity": "Standard"},
  {"name": "ไม้เบสบอล III", "rarity": "Heroic"},
  {"name": "ปากฉลาม IV", "rarity": "Epic"},
  {"name": "ดาบคาตานะ V", "rarity": "Limited"},
  {"name": "ดาบคาตานะ VI", "rarity": "Limited"},
  {"name": "ปืนพก AP", "rarity": "Legend"},
  {"name": "ปืนช็อตไฟฟ้า", "rarity": "Legend"},
  {"name": "น้องหมูเด้ง EXP×2.5", "rarity": "Legend"},
  {"name": "มีดพร้า Valentine's X", "rarity": "Ultimate"}
]
