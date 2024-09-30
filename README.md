# Shoghlana
A job recommendation website
كيفية تشغيل مشروع "شغلانة"
أولاً: التأكد من تنزيل أخر اصدار من البرامج التالية (توجد لينكات اليها)
1-	البايثون Python: https://www.python.org/downloads
•	عند تنزيل البايثون تأكد من العلامة علي ((Add to PATH
2-	 https://www.apachefriends.org/download.html: Xampp
3-	الديجانجو: أ- افتح الcmd  ثم اكتب  py -m pip install Django

ثانياً: فُك ضغط الملف و اضغط علي ملف المشروع
ثالثاً: في خانة مصار الملف من فوق اكتب بدلها كلمه cmd. سيفتح الcmd  علي مصار الملف.
رابعاً: اكتب هذه الأوامر بالترتيب في ال cmd:
1-	python -m venv venv
•	ثم انتظر بضع ثواني حتي يظهر مصار الملف ثانية.
2-	.\venv\Scripts\activate
•	ستظهر كلمة “(venv)” قبل مصار الملف
3-	pip install -r requirements.txt 
•	سينزل بعد الأساسيات البسيطة لتشغيل المشروع
خامساً: ارجع للملف نفسه ثم خذ نسخة ((copy من فايل (.example.env) ثم الصقه ثانية في الملف و لكن غير اسمه ليصبح ( (.env
سادساً: افتح الxampp ، ثم اضغط Start  التي علي نفس سطر الApache . ثم اضغط Start  التي علي نفس سطر الMYSQL 
سابعاً: اضغط علي زر Admin التي علي نفس سطر الMYSQL 
سيفتح صفحة phpMyAdmin 
اضغط علي new  ثم اضف هذا النص في مربع النص لاسم قاعدة البيانات : job_recommendation ثم اضغط create 
ثامناً: ارجع للcmd  ثم اكتب : python manage.py migrate
تاسعاً: اكتب في الcmd  : python manage.py runserver
سيظهر لك لينك إذا فتحته في المتصفح فسوف يفتح لديك
http://127.0.0.1:8000/ وعادة يكون اللينك :

