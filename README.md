### hoverfly
---
https://github.com/SpectoLabs/hoverfly


```sh
hoverctl start
hoverctl mode capture

curl --proxy http://localhost:8500 http://time.jsontest.com
hoverctl logs

hoverctl logs

hoverctl export simulation.json
hoverctl stop

hoverctl mode capture --headers "User-Agent,Content-Typ,Authorization"
hoverctl mode capture --all-headers

hoverctl export echo.json --url-pattern "echo.jsontest.com"
hoverctl export api.json --url-patten "(.+).jsontest.com"

hoverctl start
hoverctl import simulation.json

hoverctl import https://example.com/example.json

curl --proxy localhost:8500 http://time.jsontest.com
```

```sh
mkdir $GOPATH/src
cd $GOPATH/src
mkdir -p github.com/SpectoLabs/
cd github.com/SpectoLabs/
git clone https://github.com/SpectoLabs/hoverfly.git
cd hoverfly
make build
make test
brew install ruby
brew install python
```

```json
{
  "time": "02:07:28 PM",
  "milliseconds_since_epoch": 148224848562,
  "date": "12-20-2016"
}
```


