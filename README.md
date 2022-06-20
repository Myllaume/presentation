## Go

```
git clone --recurse-submodules https://github.com/Myllaume/presentation/ presentation
```

```
init.sh
pandoc.sh
```

```
cd reveal && npm start
nodemon content.md --exec "sh pandoc.sh"
```

Write content on `content.md`.

Pandoc documentation : https://pandoc.org/MANUAL.html#structuring-the-slide-show