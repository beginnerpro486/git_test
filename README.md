echo "# git_test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:beginnerpro486/git_test.git
git push -u origin main
git add "Hello Odin!"