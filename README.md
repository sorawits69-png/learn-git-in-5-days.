# 1. ประกาศตัวตน (ทำครั้งแรกครั้งเดียว)
git config --global user.name "Sorawit Sitthiaxorn"
git config --global user.email "your-email@example.com"

# 2. เริ่มต้นระบบ Git ในโฟลเดอร์
git init

# 3. ดึงไฟล์ทั้งหมดเตรียมเซฟ
git add .

# 4. บันทึกประวัติเวอร์ชัน
git commit -m "Initial commit: Learn Anything in 5 Days Challenge"

# 5. เปลี่ยนชื่อ Branch หลักให้เป็น main
git branch -M main

# 6. เชื่อมกับ GitHub Repo ของคุณ (ก๊อปปี้ URL มาจากหน้าเว็บ GitHub ที่เพิ่งสร้าง)
git remote add origin https://github.com/<ชื่อ-Username-ของคุณ>/<ชื่อ-Repo-ของคุณ>.git

# 7. ส่งไฟล์ขึ้น GitHub
git push -u origin main
