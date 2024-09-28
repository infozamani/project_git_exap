# learn_github
<!-- cmd -->
git --version
git config --global user.name "fariborz zamani"
git config --global user.email "fariborz499@gmail.com"
git config --list
git config --global core.editor "C:\Program Files\Microsoft VS Code1\bin\code"
git clone https://github.com/infozamani/learn_github.git
cd learn_github
code .
<!-- vs.code -->
git  status 
git add .
git commit -m "add test" 
git push
<!-- --hellp -->
git --help
<!-- uplode files or push -->
md new_project
git init
<!-- github.com  -->
create test_projectپروژه ایجاد شده بدون ردمی ایجاد کنید و سپس برای ایجاد آن در شاخه چروژه از دستور زیر استفاده می کنیم
echo "# new_project" >> README.md
برای اینکه تمامی فایل های داخل پوشه اضافه شود 
git add .
git status متوجه تغییرات می شوید
git commit -m "first commit"
git branch -M main
git status روی برنچ مین قرار می گیرد
git remote add origin https://github.com/infozamani/new_project.git
git push     Update remote refs along with associated objects
 git push --set-upstream origin main فقط   یکبار برای هر برنچ
git pull     Fetch from and integrate with another repository or a local branchواکشی و ادغام با یک مخزن دیگر یا یک شعبه محلی
git fetch     تغییرات را نشون میده ولی  به این جا انتقال نمیده ولی پول انتقال میده
git diff تغییرات را نسبت به قبل نشون میده

