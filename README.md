# TestesDocker

Repositório com elementos para testar inicialmente como funciona o docker. De maneira básica e simples.

Siga os passos:

git clone https://github.com/PedroIeremis/TestesDocker.git

cd TestesDocker

docker build -t nx .

docker run -d -p 8080:80 nx

Abra navegador e acesse: localhost:8080
