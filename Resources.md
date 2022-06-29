**The file will have its original line endings in your working directory**
**warning: LF will be replaced by CRLF in ...**

git config core.autocrlf true <-- single developer on windows machine, turns warning off
git config --global core.autocrlf false <-- windows programer on Windows only project, turns off functionality

**start JSON axios Server**
json-server --watch db.json --port 3001
