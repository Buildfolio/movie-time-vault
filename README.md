# Movie Time — เวลาดูหนัง

Vault สำหรับเก็บหนังและอนิเมชันที่อยากดู ดูแล้ว และชอบมาก
แยกตามประเภท (หนัง / อนิเมชัน) และแยกตามอารมณ์ เช่น เบาสมอง ดราม่า แอ็กชัน

## เปิดใน Obsidian อย่างไร

1. เปิด Obsidian
2. Open folder as vault เลือกโฟลเดอร์ `movie-time-vault`
3. เปิดโน้ต [[Movie-Time]] เป็นหน้าแรก
4. เปิด Graph view เพื่อดูว่าโน้ตทั้งหมดโยงกันอย่างไร

## เพิ่มเรื่องใหม่

1. คัดลอกเทมเพลตจาก [[Template-Movie]] หรือ [[Template-Animation]]
2. วางไฟล์ใหม่ในโฟลเดอร์ `Movies/` หรือ `Animation/`
3. ตั้งชื่อไฟล์เป็นภาษาอังกฤษเท่านั้น (ห้ามใช้ชื่อไฟล์ภาษาไทย)
4. กรอก frontmatter: status, rating, genres, moods, platform, thai_dub, thai_sub
5. เพิ่มลิงก์ `[[...]]` ไปยังโน้ตหมวดอารมณ์และโน้ตสถานะที่เกี่ยวข้อง
6. เพิ่มชื่อเรื่องในรายการของ [[Movies]] หรือ [[Animation]] ด้วย

## โครงสร้างโฟลเดอร์

- `Movie-Time.md` — ฮับกลางของ vault นี้
- `Movies/` — หนัง live-action + [[Movies]]
- `Animation/` — อนิเมชัน + [[Animation]]
- `Moods/` — แยกตามอารมณ์: [[Feel-Good]], [[Drama]], [[Action]], [[Romance-Comedy]], [[Thriller-Horror]], [[SciFi-Fantasy]], [[Family-Warm]], [[Documentary]]
- `Status/` — แยกตามสถานะ: [[Watchlist]], [[Watched]], [[Favorites]]
- `Templates/` — [[Template-Movie]], [[Template-Animation]]
- `.obsidian/` — ตั้งค่า Obsidian ของ vault นี้

## กติกาไฟล์

- ชื่อไฟล์ภาษาอังกฤษเท่านั้น ชื่อไทยใส่ไว้ใน title ข้างในโน้ต
- ทุกโน้ตเรื่องใหม่ต้องมี frontmatter และลิงก์กลับไปหาฮับของตัวเอง
- สถานะมี 3 แบบ: `watchlist` (อยากดู) / `watched` (ดูแล้ว) / `favorite` (ชอบมาก)
