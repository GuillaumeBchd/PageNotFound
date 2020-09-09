#PageNotFound

This directory contains instructions on how to make an nginx "page not found" docker.

use :
```
cd .../PageNotFound
docker build -t guillaumebchd/PageNotFound:1.0.0 .
docker run -d -p 80:80 guillaumebchd/PageNotFound
```

credit for the web page goes to : [https://codepen.io/uiswarup/pen/XWdXGGV?editors=1100](https://codepen.io/uiswarup/pen/XWdXGGV?editors=1100)
