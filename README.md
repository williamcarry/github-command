…or create a new repository on the command line

echo "# github-command" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/williamcarry/github-command.git

git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/williamcarry/github-command.git

git push -u origin master

建立仓库命令

curl -u 'username' https://api.github.com/user/repos -d '{"name":"RepoName"}'

上传至github中

git remote add origin git@github.com:haoxiaolu/doccenter

git fetch

git commit -a -m "add file"

git add .

git push

