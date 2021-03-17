
##

```
$ cd proxy
$ go mod init proxy
go: creating new go.mod: module proxy

$ . ~/proxy.txt

goproxy_snail007/proxy (master)
$ go get gopkg.in/alecthomas/kingpin.v2
go: downloading gopkg.in/alecthomas/kingpin.v2 v2.2.6
go: gopkg.in/alecthomas/kingpin.v2 upgrade => v2.2.6
go: finding module for package github.com/alecthomas/template
go: finding module for package github.com/alecthomas/units
go: downloading github.com/alecthomas/units v0.0.0-20210208195552-ff826a37aa15
go: downloading github.com/alecthomas/template v0.0.0-20190718012654-fb15b899a751
go: found github.com/alecthomas/template in github.com/alecthomas/template v0.0.0-20190718012654-fb15b899a751
go: found github.com/alecthomas/units in github.com/alecthomas/units v0.0.0-20210208195552-ff826a37aa15

$ go build



```


`./proxy http -t tcp -p "0.0.0.0:38080" -T tcp -P "web-proxy.ap.softwaregrp.net:8080"`


`./proxy http -t tcp -p "0.0.0.0:38080" -T tcp -P "web-proxy.ap.softwaregrp.net:8080"`