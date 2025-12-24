
cd /path/to/portfolio-yohanes
git init
ls -la .git/
git add .
git add index.html style.css script.js images/
git commit -m "Initial commit: Website portfolio Yohanes Yosua Karno dengan HTML, CSS, JS"
git remote add origin https://github.com/Yohanes-Yosua-Karno/portfolio-yohanes.git
git remote -v
git branch -M main  # Pastikan branch utama bernama main
git push -u origin main
