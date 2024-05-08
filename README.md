echo "# how_to_upload_Projects_using_git_bash_on_github" >> README.md


git init
git add .
git status
git commit -m "first commit"
git status
git branch -M main
git remote add origin https://github.com/RahulDadhich26/how_to_upload_Projects_using_git_bash_on_github.git
git push -u origin main
// gives you error
git switch master
git add .
git status
git init
git remote add origin-push
git push main
git branch -M master
git status
git remote add origin https://github.com/RahulDadhich26/how_to_upload_Projects_using_git_bash_on_github.git
git push -u origin master
