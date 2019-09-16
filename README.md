## Source
[Part I](https://www.youtube.com/watch?v=IFM9hbapeA0&t=879s)

[Part II](https://www.youtube.com/watch?v=xoxJxifNWPE&t=10s)

[Part III](https://www.youtube.com/watch?v=j9d7e9_fVu0&t=1490s)

[Part IV](https://www.youtube.com/watch?v=OwllppdFQ3U&t=1s)

## Tool
- VScode: [Live SASS Compilter](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
```json
    "liveSassCompile.settings.formats": [{
        "format": "compressed",
        "extensionName": ".min.css",
        "savePath": "/dist/css"
    }],
    "liveSassCompile.settings.generateMap": false,
```
## Question

- Why put in front of the file name `_` or `_` in **scss**/**css**?
  - The `_ (underscore)` is a partial for scss. That means the stylesheet its **going to be imported** (`@import`) to a main stylesheet i.e. styles.scss. The advantage on using partials is that you can use many files to **organize** your code and everything will be compiled on a single file.