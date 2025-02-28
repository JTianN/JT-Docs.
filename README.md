####################################################
# การ Upload ขึ้น GitHub
- Initial เบื้องต้น
- git remote add origin https://github.com/USERNAME/NEW-REPO.git   (Copy จาก repo ที่สร้างไว้)
- git remote -v         --> ตรวจดู URL ตรงไหม
- git branch            --> เช็คว่า เป็น main,master
- git branch -M main     --> ตังชื่อ main
# Upload file
- git add .
- git commit -m "Initial commit"
- git push -u origin main
# กรณี URL ชี้ไม่ตรง
- git remote -v
- git remote remove origin
- git remote add origin https://github.com/USERNAME/NEW-REPO.git       --> ใส่อันใหม่ของเรา
# การ clone
- git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
- cd YOUR_REPOSITORY
# Make requirement file python
- pip freeze > requirements.txt
# การสร้างไฟล์ requirement.txt (เฉพาะที่ใช้ใน code)
CMD1 : pip install pipreqs
CMD2 : pipreqs . --force
CMD3 : pip freeze > requirements.txt เอาทุกตัวที่เราเคยติดตั้ง
