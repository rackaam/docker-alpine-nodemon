Docker Alpine Nodemon

`docker run -v <path_to_app>/:/app  rakam/alpine-nodemon`

`<path_to_app>` must contain a `package.json` with the `scripts.start` property:
```
{
  "name": "app-name",
  "version": "0.0.1",
  "scripts": {
    "start": "node src/app.js"
  }
}
```
