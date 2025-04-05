---
title: "scraper"
description: "Web image scraping tool"
date: "Mar 18 2024"
demoURL: "https://markovidakovic.com"
repoURL: "https://github.com/markovidakovic/scraper"
---

web image scraper program

### build the program

```
$ go build ./cmd/scraper/main.go
```

### run the program

- flag options:
  - output file format: txt,csv,json,xml (default: txt)
  - download: true,false (default:false) 

```
$ ./main -output-file-format=json -download=true
```

