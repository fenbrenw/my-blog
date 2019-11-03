---
categories:
- Linux
- Development
date: "2017-08-25"
disableComments: false
slug: lines-of-code
tags:
- linux
- hugo
title: Milano Has 230 Lines of Code
---

```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
       15 ./layouts/partials/paginator.html
       20 ./layouts/partials/footer.html
        0 ./layouts/partials/head_custom.html
        0 ./layouts/partials/foot_custom.html
        7 ./layouts/partials/css.html
       21 ./layouts/partials/header.html
       41 ./layouts/_default/single.html
       21 ./layouts/_default/list.html
       16 ./layouts/_default/terms.html
        5 ./layouts/404.html
       78 ./static/css/style.css
       12 ./static/css/fonts.css
      236 total
```
