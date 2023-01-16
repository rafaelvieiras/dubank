# Dubank 💳

Este projeto tem como objetivo recriar a interface do site do **Nubank**, com o intuito de estudar e aplicar os conceitos de HTML, CSS e JavaScript. Utilizamos o [parcel](https://parceljs.org/) para gerenciar os arquivos, criar um server de desenvolvimento e empacotar releases.

## Como subir a aplicação para desenvolvimento 🚀

- Faça o clone do projeto para sua máquina.
- Instale as dependências usando o comando `npm install`.
- Rode o comando `npm start` para iniciar o server de desenvolvimento.
- Abra o seu navegador e acesse http://localhost:1234 para visualizar a aplicação.
  
## Guia de desenvolvimento/colaboração 📚

Este projeto adota o padrão de commits [Conventional Commits](https://www.youtube.com/watch?v=sbK9h45Jc5o), semelhante ao usado pelo projeto do [Angular 5+](https://gist.github.com/brianclements/841ea7bffdb01346392c). Isso significa que os commits devem seguir uma **estrutura específica**, sempre em **inglês**, para facilitar a compreensão e organização do código. 

Alguns exemplos de padrão de commits incluem:

- `$ git commit -m "feat: Adiciona nova feature de cadastro de usuário"`
- `$ git commit -m "fix: Corrige bug na tela de login"`
- `$ git commit -m "ci: Atualiza configurações do CI/CD"`

Não se preocupe com ferramentas de commit, apenas siga esse padrãozinho de **feat**, **fix**, **ci**.

Cada nova feature implementada deve ser submetida via **Pull Request** para o branch de desenvolvimento (**develop**). Para fazer isso, siga os seguintes passos:

- Crie uma nova branch a partir do branch **develop**, com o nome da sua feature (ex: **ft/cadastro-usuario**).
- Faça as alterações necessárias e faça o commit seguindo o padrão Conventional Commits.
- Abra um Pull Request para o branch develop, descrevendo as suas alterações e justificando a necessidade da feature.
- Aguarde a revisão e feedback dos outros membros do time antes de fazer merge.

## Estrutura de pastas 📁

A estrutura de pastas do projeto Dubank é bastante simples e organizada, facilitando a localização e manutenção dos arquivos. A pasta principal é a `src`, que contém os arquivos principais da aplicação. Dentro dela, encontramos o arquivo `index.html`, que é o ponto de entrada da aplicação.

A pasta `styles` contém o arquivo `style.css`, responsável por dar estilo e forma à interface da aplicação. Já a pasta `scripts` contém o arquivo `app.js`, onde são escritas as funcionalidades e lógicas do código.