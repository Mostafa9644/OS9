# OS9
# مصطفی زوار
# تمرین شماره ی 9
__سوال 1__
<br>
<br>
`chown:`
دستوری برای تغییر دادن مالک و گروهِ فایل ها و دایرکتوری ها
<br>
`chown -v`:
تغییرات اعمال شده را نشان میدهد
<br>
`chown -R:`
انجام تغییرات به صورت بازگشتی
<br>
`gpasswd:`
دستوری برای مدیریت گروه ها، برای تغییر کابربران گروه و همینطور تغییرات رمز
<br>
`gpasswd -a:`
اضافه کردن کاربر به گروه های مختلف
<br>
`gpasswd -r:`
حذف رمز
<br>
`gpasswd -d:`
حذف کاربر از گروه
<br>
<br>
__سوال 2__
<br>
`whoami` با این دستور نام کاربری خود را برای اطمینان پیدا میکنیم
<br>
`id <id that found>` 
<br>و با گذاشتن نام کاربری که پیدا کردیم اینجا اطلاعات کامل میگیریم
<br>
__سوال 3__
<br>
`sudo useradd oslab`
دستور ایجاد کاربر
<br>
`sudo passwd oslab`
دستور برای تعیین رمز
<br>
__سوال 4__
<br>
`sudo groupadd sadjad`
`sudo groupadd Uni`
<br>
دستور برای تشکیل دو گرو مد نظر
<br>
`sudo usermod -G sadjad,Uni oslab`
<br>
دستور برای اضافه کردن کاربر به دو گروه
<br>
