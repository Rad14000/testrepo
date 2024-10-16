echo "# testrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Rad14000/testrepo.git
git push -u origin main
