![Logo GoStack 12](https://i.imgur.com/UuhPCqe.png)

<h1 align="center">
  GoMarketplace
</h1>

<div align="center">
 "Ao infinito e além 🚀"
</div>

&nbsp;

<div align="center">
  <img src="https://i.imgur.com/6bvhK6h.gif" />
<!-- ![Preview App](https://i.imgur.com/6bvhK6h.gif) -->
</div>

## Sobre 🤓

Esta é uma aplicação web desenvolvida no GoStack 12 do Rocketseat, onde praticamos o que aprendemos com os fundamentos do React Native. Nossa aplicação simula um simples e-commerce onde você pode adicionar produtos ao carrinho, usando tudo que foi aprendido como hooks, contextos, componentes, estado e imutalibilidade.

## Como posso usar sua aplicação 🔧🆙 ?

### Requisitos:

Você dependerá de um série de configuração para preparar o ambiente pra rodar a aplicação, vou deixar um link onde você terá a preparação do ambiente https://react-native.rocketseat.dev/. Fora isso ainda terá que ter:

&nbsp;

No seu terminal faça um clone do projeto

```bash
git clone https://github.com/brunoJSX/GoMarketplace
```

Entre na pasta e dê o comando para instalar todas as dependências.

```bash
yarn
```

Agora vamos rodar nosso json-server para nos prover de uma fake api.

```bash
yarn json-server server.json -p 3333
```

Edite o arquivo ./src/services/api.ts onde fica o endereço de conexão para nossa fake api. O endereço a ser utilizado dependerá de onde irá rodar a aplicação.

- Emulador android -> Usar localhost.
- Android físico -> Ip local da sua máquina.

Em seguida basta rodar o comando

```bash
yarn start
```

E por fim

```bash
yarn android
```

E pronto!!! A primeira execução demorará um pouco por causa do build.
&nbsp;

<h2 align="center">
 Gostou? 🥳🚀
</h2>

<div align="center">
 Se gostou avalie com uma linda 🌟, dessa forma você irá me incentivar a publicar mais projetos cada vez melhores.
</div>
