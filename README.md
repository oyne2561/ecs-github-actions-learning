image作成
```
cd api
```
```
docker image build -t github-actions-pra-api .
```

container 起動
```
docker container run --rm -p 8080:8080 github-actions-pra-api
```