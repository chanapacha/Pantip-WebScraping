# Pantip-WebScraping
ดึงข้อมูลบน Website Pantip โดยใช้ BeautifulSoup และ Selenium 
# ขั้นตอน
1. ใช้ Selenium ช่วยในการ scroll down เพื่อให้ได้จำนวน URL Link ตามที่ต้องการ ผ่านหน้า Pantip Search Engine
2. ดึงข้อมูลในแต่ละ URL Link เพื่อเอา
   - Name: ชื่อกระทู้
   - Story: รายละเอียดกระทู้
   - User ID: ID ของ user
   - Message: Comment (ไม่รวม comment ย่อย)
3. Export data
