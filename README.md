# firebase-push-gen


Quick little script to set H2 push headers for apps deployed to firebase.


```bash

npx firebase-push-gen http://127.0.0.1:8080
```

`http://127.0.0.1:8080` is the default URL, but any URL can be used, including deep links.
Tested using [local-web-server](https://www.npmjs.com/package/local-web-server) as it supports HTML push-state history and index.html redirects.

