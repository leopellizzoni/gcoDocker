# gcoDocker


Criar a imagem do docker 
```
docker build -t gco-docker-site-bootstrap .
```

Executar o container da imagem criada
```
docker run -d -p 8080:80 gco-docker-site-bootstrap
```
