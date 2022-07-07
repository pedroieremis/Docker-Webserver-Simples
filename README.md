## Suba o Container com Docker

Repositório com html e css para subir com o docker usando o nginx

Siga os passos abaixo para subir o container e acessar explicações e outras dicas:

```shell
git clone https://github.com/PedroIeremis/TestesDocker.git

cd TestesDocker

docker build -t nx .

docker run -d -p 8080:80 nx
```

Abra navegador e acesse: localhost:8080
