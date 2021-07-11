git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/blueskyxi3/controller-demo.git
git push -u origin main




go mod vendor
go build -ldflags "-s -w" -v -o crontab-controller .