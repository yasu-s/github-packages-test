# 概要

Github パッケージリポジトリを使用したサンプルです。  


# コマンド

## パッケージ公開コマンド

```bash
npm publish
```

## Docker起動

```bash
cd docker
docker-compose up --build
```

## DockerイメージPush

```bash
cd docker
docker build -t docker.pkg.github.com/yasu-s/github-packages-test/test-server:1.0.0 .
docker push docker.pkg.github.com/yasu-s/github-packages-test/test-server:1.0.0
```

# 参考URL

* https://help.github.com/ja/articles/about-github-package-registry
* https://help.github.com/ja/articles/configuring-npm-for-use-with-github-package-registry
* https://help.github.com/ja/articles/configuring-docker-for-use-with-github-package-registry
