## jyskwon.github.io

Jean's personal webpage. I am using Jekyll, a static website generator.

## checking changes made locally

```sh
bundle install && jekyll serve
```
or, if you want to use Docker
```sh
docker run --rm -p 4000:4000 -v "$(pwd):/src" -it zxzl/kixlab-homepage jekyll serve --host=0.0.0.0
```

Then visit `localhost:4000` in the browser.
