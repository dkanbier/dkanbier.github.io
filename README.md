[![Build Status](https://travis-ci.org/dkanbier/dkanbier.github.io.svg?branch=master)](https://travis-ci.org/dkanbier/dkanbier.github.io)

Jekyll source for [denniskanbier.nl](https://denniskanbier.nl), hosted on GitHub Pages.

Uses remote customized theme: [jekyll-uno](https://github.com/dkanbier/jekyll-uno)

To run in local in docker:

```
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve --watch --drafts
```
