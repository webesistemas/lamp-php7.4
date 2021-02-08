# lamp-php7.4

## PHP 7.4.15, Composer, mysql 5.7 e phpmyadmin

---
### Pastas
- src: pasta raiz do servidor onde ficarão seus códigos PHP
- data: pasta onde o mysql criará os arquivos do banco de dados

Executando o projeto
--------
Esse é um ambiente Docker funcional, ou seja, basta rodar os comandos para subir o container da aplicação e acessar a URL do projeto no navegador.

Para rodar o ambiente, é necessário ter o Docker Compose instalado, e rodar o seguinte comando:
> docker-compose up -d

Agora basta acessar a URL abaixo para visualizar a página inicial no servidor:
> http://localhost

Para interagir no console do servidor e poder interagir com o Composer, execute o seguinte comando:
> docker exec -it php /bin/bash

