## Implementação Web com Docker

Repositório com html e css simples para subir em Container Docker. Neste caso, usando o webserver da nginx. Siga os passos abaixo para obter o repostório e subir a Infraestrutura.

---

Para clonar o repositório localmente:
```shell
git clone https://github.com/pedroieremis/Web-Docker.git
```

Navegue ao diretório do repositório clonado:
```shell
cd Web-Docker/
```

Construa a Imagem:
```shell
docker build -t nx .
```

Suba a Infraestrutura:
```shell
docker run -d -p 8080:80 nx
```

__Acesse a Infraestrutura:__

Abra navegador e acesse: localhost:8080
