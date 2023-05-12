# Go- jscollector

A simple Go tool which collects all Javascript files from any domain.

### Installation
```
go get -u github.com/YashV1729/Go-jscollector
```

### Usage

```
Go-jscollector -d https://target.com
```

### We can also pipe the response into other tools, for instance:-

- `Go-jscollector -d https://google.com | wc -l`
- `Go-jscollector -d https://google.com | httprobe`
- `Go-jscollector -d https://google.com > js.txt`

