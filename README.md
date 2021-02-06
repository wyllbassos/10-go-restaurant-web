# 10-go-restaurant-web
Nesse desafio, você irá desenvolver mais uma aplicação, a GoRestaurant. Agora você irá praticar o que você aprendeu até agora no React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).  Essa será uma aplicação que irá se conectar a uma fake API, e exibir os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.


Utilizando uma fake API
Antes de tudo, para que você tenha os dados para exibir em tela, criamos um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixamos instalado no seu package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para uma rota /foods. Para executar esse servidor você pode executar o seguinte comando:

  yarn json-server server.json -p 3333
