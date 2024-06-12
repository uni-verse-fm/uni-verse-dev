# Uni-verse development environment

This is a development environment for working on uni-verse that's de-coupled from any other repos.

Clone it recursively to work on uni-verse thanks to a docker-compose stack:

```
git clone --recurse-submodules https://uni-verse-fm/uni-verse-dev

cd uni-verse-dev

docker compose up -d
```

You can then modify the code in `uni-verse-frontend` or `uni-verse-api` and the containers will pick it up.

Learn more in [the wiki](https://uni-verse-fm.github.io/docs/contribute) !
