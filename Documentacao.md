Este projeto foi realizado por Leonardo de Sousa Marques, a ser submetido para a empresa Dayback.
Nesta documentação, serão descritos os passos para que a aplicação criada em Laravel, para uma sistema de carregadores, possa ser utilizada.

1) Primeiramente, é necessário ter um programa que hospede o Banco de Dados em um servidor. Para esse projeto, utilizou-se o [**XAMPP**](https://www.apachefriends.org/pt_br/index.html).
2) Ao baixar o XAMPP, MySQL, PHP e Apache são instalados em conjunto.
3) Em 'http://localhost/phpmyadmin/', é necessário criar um Banco de Dados com o nome **daybackcarregadores**.
4) Em seguida, é necessário instalar o [**Composer**](https://getcomposer.org/), para realizar os comandos referentes ao Laravel.
5) Com tudo instalado, baixe a pasta "DaybackAPP" neste repositório com todos seus arquivos e, na mesma, rode o terminal.
6) Com o banco criado e os arquivos instalados, é necessário conectar o projeto ao Servidor, a partir do código: `php artisan serve`. Acesse o link fornecido para observar as páginas da aplicação.
7) Para passar as tabelas para o Banco de Dados, rode no terminal `php artisan migrate`.
8) A partir de agora, já é possível realizar todas as funções descritas na aplicação (Criar, Ler, Editar e Remover dados relacionados aos carregadores).
9) A fim de provar sua eficácia, neste mesmo projeto segue um arquivo JSON para utilizar no POSTMAN (Collection), em que é criado, editado e deletado o mesmo arquivo (observe no servidor) — verifique se os IDs estão corretos, pois pode haver alteração.
10) Abaixo, seguem alguns Screenshots da aplicação rodando no servidor.
