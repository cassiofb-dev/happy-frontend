## O que é?
NLW (Next Level Week), é um evento organizado pela [Rocketseat](https://rocketseat.com.br/) aonde milhares de devs se reúnem para aprender a desenvolver uma aplicação fullstack.

O evento dura uma semana com vídeos diários para o aprendizado mais didático e focado quanto possível. Após um período de tempo, os vídeos saíram do ar essa estratégia incentiva os participantes a completarem todo conteúdo do evento.

# Dia 01

 1. [Apresentação do projeto](#apresenta%C3%A7%C3%A3o-do-projeto)
 2. [Ambiente de desenvolvimento](#ambiente-de-desenvolvimento)
 3. [Back-end, front-end e API](#back-end-front-end-e-api)
 4. [O que é React?](#o-que-%C3%A9-react)
 5. [Por que usar TypeScript?](#por-que-usar-typescript)
 6. [Criando um projeto com ReactJS e TypeScript](#criando-um-projeto-com-reactjs-e-typescript)
 7. [Tarefas](#tarefas)

## Apresentação do Projeto

### Inspiração

Durante a NLW ocorrerá os dias das crianças, sendo assim a Rocketseat decidiu fazer uma aplicação relacionada com crianças.

Em uma conversa interna do time da Rocketseat, o grande Maykão The Brito falou sobre suas visitas aos orfanatos.

### O projeto

O nome do projeto é Happy (Happy de feliz com app de aplicação no meio), uma aplicação web e mobile. Ele tem como objetivo aproximar o publico geral dos orfanatos. Seu lema é:

> Leve a felicidade para o mundo.

## Ambiente de Desenvolvimento

É aconselhável usar um package manager.

Requisitos:

 1. [NodeJS](https://nodejs.org/en/) - LTS
 2. [Yarn](https://yarnpkg.com/)
 3. [VSCode](https://code.visualstudio.com/)

### Guia Windows

Copie e cole o seguinte comando para instalar o [chocolatey](https://chocolatey.org/install):

```shell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Comando para instalar o NodeJS (LTS):

```shell
choco install nodejs-lts
```

Comando para instalar o Yarn:

```shell
choco install yarn
```

Caso tenha encontrado algum problema leia o [guia oficial](https://www.notion.so/Instala-o-das-ferramentas-9eee9e25550e4477b3d0b432b605aca2).

## Back-end, Front-end e API

### Arquiteturas
![arquiteturas](https://i.imgur.com/7Net3zb.png)
### Vantagens da RESTful

 1. Flexibilidade
 2. Portabilidade
 3. Independência
 4. Escalabilidade

O back-end responde apenas os dados necessários assim podendo ser usado no mobile ou por outras páginas web.

## O que é React?

Resumidamente [React](https://github.com/facebook/react) é uma framework para interfaces utilizada na construção de [SPAs](https://en.wikipedia.org/wiki/Single-page_application) (Single Page Applications) e [PWAs](https://en.wikipedia.org/wiki/Progressive_web_application) (Progressive Web Apps) criada pelo [Facebook](https://github.com/facebook).

## Por que usar TypeScript?

### O que é?

Segundo a [microsoft](https://www.typescriptlang.org/pt/):

> TypeScript é uma linguagem código aberto construida em cima do Javascript, uma das ferramentas mais usadas do mundo, adicionando definições de tipagem estáticas

### Por que usar?

Segundo a [microsoft](https://www.typescriptlang.org/pt/):

> Tipos fornecem um jeito de descrever a forma de um objeto, fornecendo melhor documentação, e permitindo que o TypeScript valide se seu código está funcionando corretamente.
> 
> Tipar o seu código pode ser opcional no Typescript, pois a inferência de tipo permite que você obtenha muito poder sem escrever código adicional.

## Criando um projeto com ReactJS e TypeScript

Após a instalação do Node e Yarn (opcional) basta executar o comando:

```shell
yarn create react-app web --template typescript
```

Ou usando NPX:

```shell
npx create react-app web --template typescript
```

## Tarefas

 1. Criação da Landing Page
 2. Trabalhando com rotas
 3. Página com mapa

# Dia 2

Segue o 🔥[link](https://github.com/cassiofb-dev/happy-backend)🔥
