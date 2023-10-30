# try-codespaces-localstack
LocalStackをCodespacesで使ってみる試み

# Command
```sh
$ docker-compose -v
docker-compose version 1.29.2, build 5becea4c

$ localstack -v
2.3.2
```

# memo
~~devcontainerのfeaturesでlocalstackがインストールできない~~

2023/10/30時点でインストールできるようになっていた。

ただし、`Rebuild Container`がかなり遅いため、
`dockerfile`を使ってプレビルドできるようにした方が良さそう。