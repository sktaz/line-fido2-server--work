## macOSを利用しており、M2チップ搭載の端末を利用している場合
`/Users/saki/Documents/sktaz_dev/zenn_desc_line-fido2-server/line-fido2-server/server/Dockerfile
`の先頭行を下記に変更する。

```
FROM --platform=linux/amd64 openjdk:8-jdk-slim
```


##


docker build -t build-image . 

