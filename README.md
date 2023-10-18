# README

```shell
rm -rf docs/*
rm -rf blog
rm src/pages/index.js
# replace next line with a git clone of docs.zh-cn into `docs`
cp -r ../docs.zh-cn/* docs
rm docs/introduction/StarRocks_intro.md docs/TOC.md docs/README.md
yarn build
```

That's all Folks
