# List (لیست)

### [ Commend linux (دستورات لینوکس) ]( #linux-commend-دستورات-لینوکس )
1. ls
2. cd
3. clear
4. exit
5. mkdir
6. touch
7. cat
8. nano
9. echo
10. pwd
11. rm
12. ln
13. man
14. cp
15. mv
16. locate
17. history
18. find
19. tree
20. grap
21. awk



# linux commend (دستورات لینوکس)

### 1. ls
Display the list of folders and files (نمایش لیست پوشه و فایل ها)
```ruby
ls
```

* ```ls -t``` Display based on file and folder creation time (نمایش بر اساس زمان ایجاد فایل و پوشه)

* ```ls -a``` Show file and directory with more information (نمایش تمام پوشه و فایل های مخفی و قابل نمایش)

* ```ls -l``` Show file and directory with more information (نمایش فایل و دایرکتوری با اطلاعات بیشتر)

* ```ls -l -t -a ``` Sequential use (استفاده ترتیبی)

* ```ls -lta``` Combined use (استفاده ترکیبی)

* ```ls -s``` Display files and folders next to their size (نمایش فایل و پوشه ها در کنار حجم انها)

---
### 2. cd
Go to the desired location in the terminal (رفتن به لوکیشن مورد نظر در ترمینال)
```ruby
cd <name location switch>
```

Back to the previous folder (برگشت به پوشه قبلی)
```ruby
cd ..
```

Back to homework (برگشت به خانه کاری)
```ruby
cd .
```

* ```cd name-directory/name-directory``` Slash for addressing and spacing between folders (اسلش برای ادرس دهی و فاصله انداختن بین پوشه ها)

---
### 3. clear
Clear the terminal (پاک کردن ترمینال)
```ruby
clear
```

* ```ctrl``` + ```l``` Hiding data in the terminal (مخفی کردن داده ها در ترمینال)

---
### 4. exit
Rouge from the terminal (خروج از ترمینال)
```ruby
exit
```

---
### 5. mkdir
Create a folder (ساخت پوشه)
```ruby
mkdir <name-directory>
```

* ```mkdir <name-directory> <name-directory>``` Create multiple folders (ساخت چند پوشه)

---
### 6. touch
Create file (ساخت فایل)
```ruby
touch <name-file>
```

---
### 7.  cat
Print all the data of a file in the terminal (چاپ تمام داده های یک فایل در ترمینال)
```ruby
cat <name-file>
```

---
### 8. nano
Open the file in the terminal editor (باز کردن فایل در ادیتور ترمینال)
```ruby
nano <name-file>
```

* ```ctrl``` + ```o``` Save changes (سیو تغیرات)

* ```ctrl``` + ```x``` Exit the editor (خروج از ادیتور)

---
### 9. echo
Print the given text to the terminal or a text file (چاپ متن داده شده در ترمینال یا یک فایل متنی)
```ruby
echo <my-text>
```

```ruby
echo <my-text> > <file-name>
```

---
### 10. pwd
Show our location in the terminal (نمایش لوکیشن ما در ترمینال)
```ruby
pwd
```

---
### 11. rm
Delete the file (حذف فایل)
```ruby
rm <name-file>
```

Delete the empty folder (حذف پوشه خالی)
```ruby
mkdir <name-directory>
```

Delete full and empty folder (حذف پوشه پر و خالی)
```ruby
rm -r <name-directort>
```

---
### 12. ln
Link a file to a new file created with the desired name (لینک یه فایل به یک فایل جدید ایجاد شده به نام دلخواه)
```ruby
ln <name-file> <name-file>
```

---
### 13. man
Display information about Linux commands (ننایش اطلاعات دستورات لینوکس)
```ruby
man ls
```
```ruby
man cd
```
```ruby
man man
```

---
### 14. cp
Copy a file from one location to another location (کپی یک فایل از یک لوکیشن به یک لوکیشن دیگر)
```ruby
cp <location-file>/<name-file> <location-file>
```

---
### 15. mv
Transfer the file to another location (انتقال فایل به لوکیشن دیگر)
```ruby
cp <location-file>/<name-file> <location-file>
```

---
### 16. locate
Show the location of a file (نمایش لوکیشن یک فایل)
```ruby
locate <name-file>
```

---
### 17. history
Display the history of used commands (نمایش هیستوری کامند های استفاده شده)
```ruby
history
```

---
### 18. find
Find files anywhere in memory (پیدا کردن فایل در هر مکانی از حافظه)
```ruby
find -name `<name-file>`
```

---
### 19. tree
File and directory tree display (نمایش درختی فایل و پوشه ها)
```ruby
tree
```

---
### 20. grap
Find a file with a specific file extension (پیدا کردن فایل با الوگی خاص پسوند)
```ruby
grap -option *.<file-extension>
```

Find a file with a specific name (پیدا کردن فایل با الوگی خاص نام)
```ruby
grap -option <special-pattern>*
```

Find a text in all files in a directory (پیدا کردن یک متن در تمام فایل های یک پوشه)
```ruby
grap -option <my-string>*
```

Find a text in a file (پیدا کردن یک متن در یک فایل)
```ruby
grap -option <my-string> <name-file>
```

* ```-i``` Case insensitive (غیر حساس به حروف کوچک و بزرگ)

* ```-c``` The number of matches (تعداد تطابق)

*❗Control character is not mandatory (وجود کارکتر کنترلی اجباری نیست)*

---
### 21. awk
Processing the text file, including the execution of the command written in the named file (پردازش فایل متنی، از جمله اجرای دستور نوشته شده در فایل نامگذاری شده)
```ruby
awk '{ <command> }' <filename>
```

#

# file bash (bash فایل)
There are executable files in which the commands written in them are executed in the terminal (فایل هایی اجرایی هستن که دستورات نوشته شده درون انها در ترمینال اجرا میشوند)

### 1. Create file bash (bash ساخت فایل)
Create bash file with .sh extension in terminal (در ترمینال .sh با پسوند bash ساخت فایل )
```ruby
touch <name-file>.sh
```

Access the bash file to run (برای اجرا bssh دسترسی به فایل)
```ruby
sudo chmod +x <file-name>.sh
```

Run the bash file (bash اجرای فایل)
```ruby
./<file-name>.sh
```


#

# commend in bash file (bash دستورات درون فایل)

### 1. Add Commentator (اضاف کردن مفسر)
Add the bash interpreter to the file (به فایل bash اضافه کردن مفسر)
```ruby
!/bin/bash
```
*❗Note: It is required in some versions of Linux (در برخی از نسخه های لینچکس لازم می باشد)*

---
### 3. Create variable (ایجاد متغیر)
Define a new variable to the interpreter (تعریف یه متغیر جدید به مفسر)
```ruby
<variable-name>=<amount-of>
```

Example (مثال)
```ruby
a=1
```

Example (مثال)
```ruby
a="hello"
```

---
### 3. Variable value (مقدار متغیر)
Using value stored in variables (استفاده از مقدار ذخیره شده در متغیر ها)
```ruby
"$<variable-name>"
```

Example (مثال)
```ruby
echo "$a"
```

---
### 4. Print text (چاپ متن)
Text printing for better communication with the user (چاپ متن برای ارتباط بهتر با کاربر)
```ruby
echo "<my-staring>"
```

---
### 5. mathematical operations (عملیات ریاضی)
Using mathematical operations on variables of the same data type (استفاده از عملیات ریاضی بر روی متغیر های از نوع داده ای یکسان)
```ruby
$((<variable-name> <operator> <variable-name>))
```

Example (مثال)
```ruby
sum=$((a+b))
```

---
### 6. Different data type (نوع داده ای متفاوت)
Printing two variables of different data types next to each other (چاپ کنار یک دیگر دو متغیر از نوع داده ای متفاوت)
```ruby
"$<variable-name> $<variable-name>"
```

Example (مثال)
```ruby
echo "sum= $a $b"
```

*❗Note: Variables A and B are not of the same data type (از یک نوع نیستند b و a متغیر)*

---
### 7. if
The order to execute the servant if the condition is correct (دستور اجرای بنده در صورت درستی شرط)
```ruby
if ((<name-variable1> <control-character> <name-variable2>));then
  <body-commands>
elseif ((<name-variable1> <control-character> <name-variable2>));then
  <body-commands>
fi
```

Example (مثال)
```ruby
if ((a < b));then
  echo "$b"
elseif ((a > b));then
  echo "$a"
fi
```

---
### 8. for
I repeat it a certain number of times (تکرار بنده به تعداد مشخص)
```ruby
for ((<name-variable1>; <name-variable1> <control-character> <name-variable2>; <name-variable1>++));do
  <body-commands>
done
```

Example (مثال)
```ruby
for ((a=0; a < b; a++));do
  echo "$a"
done
```

---
### 9. while
I repeat until the condition is established (تکرار بنده تا زمان برقراری شرط)
```ruby
while ((<name-variable1> <control-character> <name-variable2>));do
  <body-commands>
done
```

Example (مثال)
```ruby
while ((a < b));do
  echo "$a"
done
```

---
### 10. do while
I repeat until the condition is established (تکرار بنده تا زمان برقراری شرط)
```ruby
do
  <body-commands>
done while ((<name-variable1> <control-character> <name-variable2>));
```

Example (مثال)
```ruby
do
  echo "$a"
done while ((a < b));
```

*❗Note: Then, the body of the condition is checked once (بعد یک بار اجرای بدنه شرط چک میشه)*

---
### 11. read
Reading an input from the user (خواندن یک ورودی از کاربر)
```ruby
read  <name-variable>
```

Example (مثال)
```ruby
read a
```


#

# Additional Command (دستورات تکمیلی)

**❗Note: Unnecessary for learning (غیر ضروری جهت یادگیری)**

### 1. Network
Test network connections (تست اتصالات شبکه)
```ruby
ifconfig
```

Ping test DNS (DNS تست پینگ)
```ruby
ping <DNS>
```

---
### 2. Update (اپدیت)
Ubuntu (اوبنتو)
```ruby
sudo apt update
```

Fedora (فدورا)
```ruby
sudo def update
```

---
### 3. upgrade (اپگرید)
Ubuntu (اوبنتو)
```ruby
sudo apt-get upgrade
```

Fedora (فدورا)
```ruby
sudo def upgrade
```

---
### 4. Install app (نصب برنامه)
Ubuntu (اوبنتو)
```ruby
sudo apt-get install <Package-name>
```

Fedora (فدورا)
```ruby
sudo def install <Package-name>
```

---
### 5. Uninstall app (حذف برنامه)
Ubuntu (اوبنتو)
```ruby
sudo apt-get remove <Package-name>
```

Fedora (فدورا)
```ruby
sudo def remove <Package-name>
```

---
### 6. Root (ریشه)
Permanent root access (دسترسی دایمی روت)
```ruby
sudo su -
```


#

# Fedora Linux web terminal (ترمینال تحت وب لینوکس فدورا)

### 1. terminal
A simulated terminal from Linux Fedora for practice (یک ترمینال شبیه سازی شده از لینوکس فدورا برای تمرین)

*[terminal](https://bellard.org/jslinux/vm.html?cpu=riscv64&url=fedora33-riscv.cfg&mem=256)*

#

