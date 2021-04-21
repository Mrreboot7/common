or create a new repository on the command line
echo "# common" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Mrreboot7/common.git
git push -u origin main
