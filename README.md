grdtrust.org
============

![](https://github.com/jujhars13/grdtrust.org/blob/master/logo.png?raw=true)

The website for http://grdtrust.org using:
- [Jekyll](http://jekyllrb.com/)
- Markdown
- GruntJS
- Github pages

### Building
checkout the `gh-pages` branch
```bash
docker run --rm -v $(pwd):/srv/jekyll -p 127.0.0.1:4000:4000 \
  jekyll/jekyll jekyll build
  
  docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll
```
