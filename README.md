go mod vendor
go build -ldflags "-s -w" -v -o crontab-controller .