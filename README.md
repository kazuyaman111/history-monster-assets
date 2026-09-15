# History Monster Assets — GitHub Pages Ready

ชุดรูปมอนสเตอร์ 28 ร่าง สำหรับ History Monster

## วิธีติดตั้งแบบง่ายที่สุด
1. สร้าง GitHub repository ชื่อ **history-monster-assets**
2. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดในโฟลเดอร์นี้ขึ้น repository โดยให้ `index.html`, `manifest.json`, `.nojekyll` และโฟลเดอร์ `assets` อยู่ที่ root
3. GitHub > Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save
4. รอจน Pages แสดงลิงก์ `https://kazuyaman111.github.io/history-monster-assets/`
5. ตัวเกม v3.0.2 ที่แนบมาได้ตั้ง Base URL ไว้ล่วงหน้าเป็น `https://kazuyaman111.github.io/history-monster-assets/assets`

## เปลี่ยนรูปภายหลัง
แทนไฟล์เดิมโดย **คงชื่อไฟล์และตำแหน่งเดิม** เช่น `assets/monsters/fire/stage-1/MON001.png` แล้วเพิ่มเลข `version` ใน `index.html` ของตัวเกมเพื่อเคลียร์ cache

> หมายเหตุ: รูปไฟใช้ไฟล์แยกคุณภาพสูงที่มีอยู่แล้ว ส่วนธาตุอื่นในแพ็กนี้เป็น Starter Asset ที่แยกจากภาพวิวัฒนาการ/Character Sheet เพื่อให้ระบบใช้งานได้ทันที และสามารถแทนเป็น PNG โปร่งใสคุณภาพสูงในภายหลังได้โดยไม่แก้โค้ดเกม
