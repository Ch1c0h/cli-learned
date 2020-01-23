…or create a new repository on the command line
echo "# git-commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/gerssonmg/git-commands.git
git push -u origin master
