https://github.com/jushi2/flutgit.git

 create a new repository on the command line
 echo "# flutgit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jushi2/flutgit.git
git push -u origin main


push an existing repository from the command line

git remote add origin https://github.com/jushi2/flutgit.git
git branch -M main
git push -u origin main


config git
git config --global user.email "your_email@example.com"
git config --global credential.helper cache
git config --global core.fsmonitor true


git pull

git pull -u origin main