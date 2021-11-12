### Termos de acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

# Boas vindas ao repositório da dinamica de Testes Unitários!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Atenção a cada passo, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.


---

## SUMÁRIO

- [Boas vindas ao repositório da dinamica de Testes Unitários!](#boas-vindas-ao-repositório-da-dinamica-de-testes-unitários)
  - [SUMÁRIO](#sumário)
  - [Habilidades](#habilidades)
- [Entregáveis](#entregáveis)
  - [O que será desenvolvido](#o-que-será-desenvolvido)
  - [Desenvolvimento](#desenvolvimento)
  - [Data de entrega](#data-de-entrega)
- [Instruções para entregar seu projeto:](#instruções-para-entregar-seu-projeto)
  - [Antes de começar a desenvolver:](#antes-de-começar-a-desenvolver)
  - [Durante o desenvolvimento](#durante-o-desenvolvimento)
  - [Como desenvolver](#como-desenvolver)
  - [EsLint](#eslint)
  - [Requisitos do projeto](#requisitos-do-projeto)
  - [1 - Implemente os casos de teste para a função `average`](#1---implemente-os-casos-de-teste-para-a-função-average)
  - [2 - Implemente os casos de teste para a função `numbers`](#2---implemente-os-casos-de-teste-para-a-função-numbers)
  - [3 - Implemente os casos de teste para a função `vqv`](#3---implemente-os-casos-de-teste-para-a-função-vqv)
  - [4 - Implemente os casos de teste para a função `circle`](#4---implemente-os-casos-de-teste-para-a-função-circle)
  - [5 - Implemente os casos de teste para a função `createStudent`](#5---implemente-os-casos-de-teste-para-a-função-createstudent)
  - [6 - Implemente os casos de teste para a função `productDetails`](#6---implemente-os-casos-de-teste-para-a-função-productdetails)
  - [7 - Implemente os testes para o objeto `calculator`](#7---implemente-os-testes-para-o-objeto-calculator)
  - [8 - Implemente os casos de teste e a função `myCounter`](#8---implemente-os-casos-de-teste-e-a-função-mycounter)

---

## Habilidades

Nesse projeto, você será capaz de:

- Escrever testes unitários para funções utilizando o framework de testes Jest para verificar o correto funcionamento dessas funções;
- Escrever testes e funções utilizando uma abordagem de desenvolvimento orientado a testes.

---

# Entregáveis

Para entregar o seu projeto você deverá criar um Pull Request neste repositório.

Lembre-se que você pode consultar nosso conteúdo sobre
[Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

---

## O que será desenvolvido

Você implementará vários testes unitários para garantir que as implementações das funções estão corretas.

---

## Desenvolvimento

* Nos testes unitários que não estão implementados, vocês verão comentários explicando sobre a função implementada. Não tentem rodar o `npm test` sem ter implementado nenhum teste, isso só fará estourar um erro no terminal.

* Os comandos que você utilizará com mais frequência são:
  1. `npm test` _(executa todos os testes presentes na aplicação)_
  2. `npm test path/to/file` _(executa apenas os testes presentes no arquivo path/to/file)_
    * exemplo: `npm test tests/average.spec.js`
    * exemplo: `npm test average`

---

## Data de entrega

  - Projeto individual;

  - Data de entrega para avaliação final do projeto: `16/11/2021 - 09:00h`

---

# Instruções para entregar seu projeto:

## Antes de começar a desenvolver:

1. Clone o repositório
  * `git clone git@github.com:tryber/sd-017-dinamica-tests.git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd sd-017-dinamica-tests`

2. Instale as dependências
  * `npm install`

3. Crie uma branch a partir da branch `master`
  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora crie uma branch para qual você vai submeter os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    * Exemplo: `git checkout -b joaozinho-js-unit-tests`

4. Faça as alterações em, por exemplo, alguma dos arquivos de teste que precisam de implementação. Por exemplo, a `average.spec.js` em `tests/`:

5. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (deve aparecer listado o arquivo _tests/last.spec.js_ em vermelho)
  * Adicione o arquivo alterado ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo _tests/last.spec.js_ em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto. VAMOS COM TUDO :rocket:'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

6. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin joaozinho-js-unit-tests`

7. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do repositório no GitHub
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a página de _Pull Requests_ do repositório e confira que o seu _Pull Request_ está criado

---

## Durante o desenvolvimento

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  4. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

---

## Como desenvolver

Este repositório contém um _template_ de uma aplicação **NodeJS** (observe a existência do arquivo _package.json_).
Após clonar o projeto e instalar as dependências, você não precisará realizar nenhuma configuração adicional.
Todos os arquivos estritamente necessários para finalizar o projeto já estão criados, **não** sendo necessária a criação de outros arquivos.
Você deverá implementar os testes unitários de forma a satisfazer os requisitos listados na seção **Lista de requisitos**.

Os testes estão na pasta `tests`.
O nome dos arquivos também seguem uma ordem definida. Basicamente, os arquivos de teste possuem o nome do arquivo alvo (arquivo da funcionalidade) acrescido do nome `.spec.js`.
Existirá um arquivo `src/exemplo.js` que conterá a implementação de uma função e um arquivo `tests/exemplo.spec.js` com os testes unitários referentes à função presente no arquivo `src/exemplo.js`.

Cada função possui um bloco de comentários em suas primeiras linhas explicando qual é o trabalho que a função deve realizar.

Você só deve alterar os arquivos indicados nos requisitos. **Os arquivos que não estão indicados nos requisitos não devem ser alterados, ou sua avaliação poderá ser comprometida.**

Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório. Este _Pull Request_ deverá conter a implementação dos arquivos solicitados abaixo.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

## EsLint

Usaremos o [ESLint](https://eslint.org/) para fazer a análise estática do seu código.

Para garantir a qualidade do seu código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento nós utilizamos neste projeto o linter `ESLint`. Para rodar o linter localmente no seu projeto, execute o comando abaixo:

```bash
npm run lint
```

Caso ainda fique alguma dúvida, você pode consultar nosso conteúdo sobre [`ESLint`](https://app.betrybe.com/course/real-life-engineer/eslint)

Você pode também instalar o plugin do `ESLint` no `VSCode`, bastar ir em extensions e baixar o [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

---

## Requisitos do projeto

## 1 - Implemente os casos de teste para a função `average`

A função average recebe um array (tamanho variável) e retorna a média dos valores recebidos. Caso a função receba algum valor não númerico ou um array vazio, o valor undefined deve ser retornado. Todos os resultados devem ser arredondados para valores inteiros. Ex: 4,6 vira 5; 1,3 vira 1. O arquivo `src/average.js` contém a função `average` já implementada. Implemente os testes no arquivo `tests/average.spec.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se o comportamento da função "average" está correto'.

## 2 - Implemente os casos de teste para a função `numbers`

 A função `numbers` recebe um array (tamanho variável) e retorna true se todos os parâmetros forem do tipo 'number' e false caso contrário. Essa função já está implementada no arquivo `src/numbers.js`. Escreva os testes para essa função para garantir que a implementação de `numbers` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `numbers` verifica se o retorno da função é `true` quando o array passado por parâmetro contém somente números.

## 3 - Implemente os casos de teste para a função `vqv`

Caso a função seja chamada sem nenhum parâmetro, o valor undefined deve ser retornado. O arquivo `src/vqv.js` contém a função `vqv` já implementada. Implemente os testes no arquivo `tests/vqv.spec.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se a função `vqv` retorna a frase esperada com nome e idade.

## 4 - Implemente os casos de teste para a função `circle`

A função `circle` recebe o raio de um círculo e retorna um objeto contendo suas informações (Raio, Área e Circunferência). Se não for especificado um raio, a função retorna `undefined`. Essa função já está implementada no arquivo `src/circle.js`. Escreva os testes para essa função para garantir que a implementação de `circle` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `circle` verifica se ao receber um raio, o retorno da função é um objeto com as informações corretas (Raio, Área e Circunferência).

## 5 - Implemente os casos de teste para a função `createStudent`

A função `createStudent` recebe como parâmetro um nome, e retorna um objeto contendo duas chaves:
  1. name, contendo o nome passado como parâmetro;
  2. feedback, contendo uma função que retorna a frase 'Eita pessoa boa!' ao ser chamada.

O arquivo `src/createStudent.js` contém a função `createStudent` já implementada. Implemente os testes no arquivo `tests/createStudent.spec.js` de forma que garanta que a implementação de `createStudent` está correta.

  **O que será avaliado**

  * Será validado se a função `createStudent` retorna o objeto esperado.

## 6 - Implemente os casos de teste para a função `productDetails`

A função `productDetails` recebe duas strings que representam nomes de produtos, e retorna um array contendo dois objetos com os detalhes dos respectivos produtos:

```javascript
productDetails('Alcool gel', 'Máscara') // Retorna:
  [
    {
      name: 'Alcool gel'
      details: {
        productId: 'Alcool gel123'
      }
    },
    {
      name: 'Máscara'
      details: {
        productId: 'Máscara123'
      }
    }
  ]
```

Essa função já está implementada no arquivo `src/productDetails.js`. Escreva os testes para essa função no arquivo `tests/productDetails.js` para garantir que a implementação de `productDetails` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `productDetails` verifica se ao receber duas strings, o retorno da função é um array de objetos e se cada objeto contém os dados necessários.

## 7 - Implemente os testes para o objeto `calculator`
Desenvolva um objeto calculator que possui quatro chaves:
  - add;
  - mult;
  - div;
  - sub.

Para cada uma delas atribua uma função que realiza a respectiva operação. A função deve receber dois inteiros e retornar um inteiro. Os resultados das divisões devem sempre ser arredondados para baixo. O arquivo `src/objCalculator.js` contém o objeto `calculator` já implementado. Implemente os testes no arquivo `tests/objCalculator.spec.js` de forma que garanta o funcionamento correto.

  **O que será avaliado**

  * Será validado se a função `objCalculator` retorna os valores esperados.

## 8 - Implemente os casos de teste e a função `myCounter`

**Agora prepare-se! Esse último requisito vai te guiar através de um longo e rico processo de desenvolvimento orientado a testes (Test Driven Development, ou TDD). Dará trabalho, mas vale a pena!**

A função myCounter possui dois loops aninhados que inserem valores dentro de um array. Eles vão adicionando valores ao array até sua condição de parada. Implemente a função `myCounter` para que a função retorne o array correto. Lembre-se de implementar os testes para garantir o funcionamento correto da função.

  **O que será avaliado**

  * Será validado se a função `myCounter` retorna os dados esperados.

