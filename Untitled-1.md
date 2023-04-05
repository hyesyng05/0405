git config --global user.name "hyesyng05"
git config --global user.email "23y30107@pcs.hs.kr"
git config --list

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hyesyng05/0405.git
git push -u origin main