# Usage
```
$ docker pull k1low/alpine-pandoc-ja
$ docker run -it --rm -v `pwd`:/workspace k1low/alpine-pandoc-ja pandoc README.md --from=markdown --to=docx --standalone --output=README.docx
$ docker run -it --rm -v `pwd`:/workspace k1low/alpine-pandoc-ja pandoc README.md --from=markdown --to=html5 --standalone --output=README.pdf 
```

# Reference
[k1LoW/docker-alpine-pandoc-ja](https://github.com/k1LoW/docker-alpine-pandoc-ja)
