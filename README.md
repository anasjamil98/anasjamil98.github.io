# Portfolio site

The source for [anasjamil98.github.io](https://anasjamil98.github.io).

Two files, `index.html` and `styles.css`, and no build step. There's no JavaScript on the page itself, no cookies, no analytics and no third-party files, so there's nothing to consent to and nothing to break.

`demo/dashboard.html` is a copy of the output of [single-file-exec-dashboard](https://github.com/anasjamil98/single-file-exec-dashboard). When that project is rebuilt, copy `dist/dashboard.html` over it.

To preview locally:

```bash
python -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000`.
