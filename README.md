####################################################
# การ Upload ขึ้น GitHub
-Initial เบื้องต้น
-git remote add origin https://github.com/USERNAME/NEW-REPO.git   (Copy จาก repo ที่สร้างไว้)
-git remote -v         --> ตรวจดู URL ตรงไหม
-git branch            --> เช็คว่า เป็น main,master
-git branch -M main     --> ตังชื่อ main
# Upload file
1.git add .
2.git commit -m "Initial commit"
3.git push -u origin main
# กรณี URL ชี้ไม่ตรง
1.git remote -v  
2.git remote remove origin
3.git remote add origin https://github.com/USERNAME/NEW-REPO.git       --> ใส่อันใหม่ของเรา
# การ clone
- git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
- cd YOUR_REPOSITORY
# Make requirement file python
- pip freeze > requirements.txt

# การสร้างไฟล์ requirement.txt (เฉพาะที่ใช้ใน code)
CMD1 : pip install pipreqs
CMD2 : pipreqs . --force
CMD3 : pip freeze > requirements.txt เอาทุกตัวที่เราเคยติดตั้ง
