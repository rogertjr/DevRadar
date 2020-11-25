<h1 align="center">DevRadar</h1>

<p align="center"> </p>

## Features
Utilização de API do Github e artifícios de localização com a utilização de:

- ⚛️ **React Js** — Livraria Javascript para construção de interfaces;
- ⚛️ **React Native** — Livraria que provê uma maneira eficiente de criar aplicações nativas para Android e iOS;
- 💹 **Node Js** — Web framework que permite utilizar javascript tanto no frontend quanto no backend;

## Descrição do Projeto

O DevRadar é um projeto que visa facilitar a busca por desenvolvedores que residem próximo a você. A aplicação detecta sua localização geográfica a partir do Google Maps e então mostra todos desenvolvedores próximos no raio de 100KM, utilizando a API do GitHub para puxar informações do perfil da pessoa. No Mobile, a aplicação exibe o mapa aonde é possível pesquisar, por tecnologias, os devs nesse raio de distância.

### Configuração
Clone o projeto em seu computador.
```bash
git clone https://github.com/rogertjr/DevRadar.git
cd DevRadar
```

### Backend
Para instalar as dependências e executar o Servidor execute:
```bash
cd backend
yarn 
yarn dev
```

### Frontend
Para instalar as dependências e iniciar o Frontend execute:
```bash
cd frontend
yarn
yarn start
```
Após o término do processo, será aberta no seu navegador uma página com o endereço `localhost:3000`.

### Mobile
Antes de executar a aplicação mobile é necessário colocar o IP do seu servidor ou computador no arquivo `src/services/api.js`, e depois executar os comandos:
```bash
# NOTA: Não é preciso executar a linha de baixo caso ja tenha o Expo (CLI) instalado
yarn global add install expo-cli
cd mobile
yarn install
yarn start
```
Após o término do processo, será aberta no seu navegador uma página com o endereço `localhost:19002`. Conecte seu emulador, ou teste o aplicativo por `LAN`: baixe o aplicativo *Expo* da Play Store ou App Store e em seguida escaneie o código QR.

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>