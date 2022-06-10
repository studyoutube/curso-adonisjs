# Curso AdonisJS

Este é um dos **[cursos](https://www.youtube.com/watch?v=y8XfJJYhXPE&t=2s&ab_channel=MatheusBattisti-HoradeCodar 'Curso AdonisJS')** sobre o **[Framework AdonisJS](https://adonisjs.com/)** ministrado pelo professor **[Matheus Battisti](https://github.com/matheusbattisti 'Repositório do professor Matheus Battisti')** do canal do YouTube **[Matheus Battisti - Hora de Codar](https://www.youtube.com/c/MatheusBattisti 'Matheus Battisti - Hora de Codar')**.

## Instalação

O [AdonisJS](https://adonisjs.com/) permite o uso com [npm](https://docs.npmjs.com/ 'Node Package Manager') ou [yarn](https://yarnpkg.com/).

Para usar o npm:

1. No diretório root (moments) destrua o arquivo yarn.lock
2. Para Instalar qualquer pacote use o comando: [`npm install [<@scope>/]<pkg>`](https://docs.npmjs.com/cli/v8/commands/npm-install 'Como instalar os pacotes usando o npm cli')
3. Para instalar todas as dependências `npm install` ou `npm i`
4. Visite o [npm](https://docs.npmjs.com/ 'Node Package Manager') para conhecer mais

Para usar o yarn:

1. No diretório root (moments) destrua o arquivo package-lock.json
2. Para instalar todas as dependências/pacotes use comando [`yarn ou yarn install`](https://yarnpkg.com/getting-started/usage#installing-all-the-dependencies)
3. Para adicionar uma dependência/pacote use o comando: [`yarn add [package]`](https://yarnpkg.com/getting-started/usage#adding-a-dependency)
4. Visite [yarn](https://yarnpkg.com/getting-started) para conhecer mais

### Em um terminal de sua preferência execute estes comandos:

#### Usando o yarn:

1. `yarn` ou `yarn install`
2. `node ace serve`
3. Este erro irá surgir: E_MISSING_ENV_VALUE: Missing environment variable "APP_KEY".
4. Gere a Key com o comando: `node ace generate:key`
5. Duplique o arquivo .env.example e renomeei para .env
6. Copie a key gerada no terminal e substitua o valor em APP_KEY no arquivo .env
7. Instale o lucid: `yarn add @adonisjs/lucid`
8. Configure o banco de dados: `node ace configure @adonisjs/lucid`
9. Em um terminal execute o comando: `node ace serve`. Este comando irá instruir ao projeto para funcionar/rodar.
10. [Para realizar o deployment](https://docs.adonisjs.com/guides/deployment)

#### Usando o npm:

1. `npm i` ou `npm install`
2. `node ace serve`
3. Este erro irá surgir: E_MISSING_ENV_VALUE: Missing environment variable "APP_KEY"
4. Gere a Key com o comando: `node ace generate:key`
5. Duplique o arquivo .env.example e renomeei para .env
6. Copie a key gerada no terminal e substitua o valor em APP_KEY no arquivo .env
7. instale o lucid `npm i @adonisjs/lucid`
8. Configure o banco de dados: `node ace configure @adonisjs/lucid`
9. Em um terminal execute o comando: `node ace serve`. Este comando irá instruir ao projeto para funcionar/rodar em modo de desenvolvimento (development)
10. [Para realizar o deployment](https://docs.adonisjs.com/guides/deployment)

Para mais informações sobre como usar um banco de dados com o [AdonisJS](https://adonisjs.com/) ou o canal do YouTube **[Matheus Battisti - Hora de Codar](https://www.youtube.com/c/MatheusBattisti 'Matheus Battisti - Hora de Codar')**.

Agradecimentos ao canal do YouTube **[Matheus Battisti - Hora de Codar](https://www.youtube.com/c/MatheusBattisti 'Matheus Battisti - Hora de Codar')** por proposionar cursos de excelente qualidade.




