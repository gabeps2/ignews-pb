# Sobre o projeto <br>

<img src="https://github.com/gabeps2/ignews-pb/blob/master/img/homepage.png?raw=true"/>
<img src="https://github.com/gabeps2/ignews-pb/blob/master/img/posts.png?raw=true"/>
<img src="https://github.com/gabeps2/ignews-pb/blob/master/img/post-example.png?raw=true"/> <br>

IGNews é um projeto desenvolvido durante o bootcamp Ignite da Rocketseat na trilha ReactJS com o objetivo de entender e aplicar o modo com o front-end está evoluindo, recebendo mais responsabilidade na apresentação dos dados e conexão com serviços externos.

O ignews é uma aplicação onde um usuário pode realizar uma assinatura para consumir conteúdo em texto, através do login social pelo Github, o usuário tem acesso a uma prévia de todos os posts da plataforma. Realizando o pagamento através do [Stripe](https://stripe.com/en-br) se tem acesso ao conteúdo completo.

## Tecnologias utilizadas

- Typescript
- ReactJS
- NextJS
- SASS
- CSS-Modules

## Serviços utilizados

- [Stripe](https://stripe.com/en-br) (API de pagamentos)
- [FaunaDB](https://fauna.com/) (Banco de dados)
- [Prismic](https://prismic.io/) (CMS)<

## Getting Started

Primeiro execute o comando ``yarn`` ou ``npm`` para instalar as dependências;

Em seguida crie um arquivo **.env.local** utilizando o arquivo **.env.example** como exemplo, preenchendo todos os campos necessários.

Por fim inicie o projeto através dos comandos: 
```bash
npm run dev
# ou
yarn dev
```

Abra [http://localhost:3000](http://localhost:3000) em seu browser para ver os resultados.
