echo "# my-repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hexiaojing2588/my-repository.git
git push -u origin main
