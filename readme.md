![新建仓库初始页面](/Picture/img.png "GitHub")

# 仓库关联操作

echo "# ideaGitDemo" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:muuyia/ideaGitDemo.git  
GitHub远程仓库创建初始分支main，创建初始文件  
git pull origin main
git push -u origin main  