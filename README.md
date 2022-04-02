<h1 align="center">Project Playground Functions</h1>

<p align="center">✔️ Concluded</p>

## 💻 Instalando o projeto

Clone o repositório:

```
git clone git@github.com:lramos33/project-playground-functions.git
```

Acesse a pasta do repositório

```
cd project-playground-functions
```

## 🚀 Habilidades

- Escrever códigos em JavaScript que usam variáveis e tipos primitivos;
- Utilizar conceitos da linguagem como a tipagem dinâmica e operadores lógicos/aritméticos/de atribuição no seu código;
- Criar códigos que usam estruturas condicionais, como o if/else;
- Manipular arrays (listas);
- Utilizar o comando for;
- Quebrar grandes problemas em pequenos;
- Utilizar a lógica de programação na resolução de problemas;
- Manipular objetos;
- Utilizar o comando for/in;
- Utilizar funções para organizar e estruturar o seu código.

## 🔧 Desenvolvimento

Neste projeto foi desenvolvido funções seguindo os requisitos especificados para o correto comportamento de cada uma delas.

## 📝 Requisitos do projeto

- [x] 1. Crie uma função usando o operador `&&`;

  Implemente na função `compareTrue`, um código que ao receber dois parâmetros booleanos deve:
    - Retornar `true` se ambos os valores forem verdadeiros;
    - Retornar `false` se um ou ambos os parâmetros forem falsos.

- [x] 2. Crie uma função que calcule a área de um triângulo;

  Escreva uma função com o nome `calcArea` que receba um valor de base (chamado `base`) e outro de altura (chamado `height`) de um triângulo e retorne o cálculo da sua área.

- [x] 3. Crie uma função que divida a frase;

  Escreva uma função com o nome `splitSentence`, a qual receberá uma string e retornará uma array de strings separadas por cada espaço na string original.

- [x] 4. Crie uma função que use concatenação de strings;

  Escreva uma função com o nome `concatName` que, ao receber uma array de strings, retorne uma string com o formato `'ÚLTIMO ITEM, PRIMEIRO ITEM'`, independente do tamanho da array.

- [x] 5. Crie uma função que calcule a quantidade de pontos no futebol.

  Escreva uma função com o nome `footballPoints` que receba o número de vitórias (esse parâmetro deverá se chamar `wins`) e o número de empates (esse parâmetro deverá se chamar `ties`) e retorne a quantidade de pontos que o time marcou em um campeonato.

  Para tanto, considere que cada vitória vale 3 pontos e cada empate vale 1 ponto.
  
- [x] 6. Crie uma função que calcule a repetição do maior número.

  Escreva uma função chamada `highestCount` que, ao receber uma array de números, retorne a quantidade de vezes que o maior deles se repete.

- [x] 7. Crie uma função de Caça ao Rato.

  Imagine que existem dois gatos, os quais chamaremos de `cat1` e `cat2`, e que ambos estão caçando um mesmo rato chamado `mouse`. Agora imagine que os animais estão em uma reta, cada um em uma posição representada por um número.

  Sabendo disso, crie uma função chamada `catAndMouse` que, ao receber a posição de `mouse`, `cat1` e `cat2`, nessa ordem, calcule as distâncias entre o rato e cada um dos gatos, em seguida, retorne qual dos felinos irá alcançar o rato primeiro (aquele que estiver mais perto do rato).
  
  Caso os gatos estejam na mesma distância do rato, a função deverá retornar a string `"os gatos trombam e o rato foge"`.

- [x] 8. Crie uma função FizzBuzz.

  Crie uma função chamada `fizzBuzz` que receba uma array de números e retorne uma array da seguinte forma:
    - Para cada número do Array que seja divisível apenas por 3, apresente uma string `"fizz"`;
    - Para cada número do Array que seja divisível apenas por 5, apresente uma string `"buzz"`;
    - Caso o número seja divisível por 3 e 5, retorne a string `"fizzBuzz"`;
    - Caso o número não possa ser dividido por 3 nem por 5, retorne a string `"bug!"`.

- [x] 9. Crie uma função que Codifique e Decodifique.

  Crie duas funções: a primeira deverá se chamar `encode` e, ao receber uma string como parâmetro, deverá trocar todas as vogais minúsculas por números, de acordo com o formato a seguir:
    - a -> 1
    - e -> 2
    - i -> 3
    - o -> 4
    - u -> 5

  A segunda função deverá se chamar `decode` e faz o contrário de `encode`.

- [x] 10. Crie uma função de Lista de Tecnologias.

  Crie uma função que recebe um array de nomes de tecnologias que você quer aprender. Essa função deve receber também um segundo parâmetro chamado `name` com um nome.
  
  Para cada tecnologia no array, crie um objeto com a seguinte estrutura:

  ```js
  {
    tech: "NomeTech",
    name: name
  }
  ``` 

  Estes objetos devem ser inseridos em uma nova lista em ordem crescente a partir do campo `tech` no objeto.

  A saída da sua função deve ser uma lista de objetos ordenada pelo campo `tech` dos objetos com o formato acima.

### Requisitos bônus:

- [x] 11. Crie uma função de Número de Telefone.

  Crie uma função chamada `generatePhoneNumber` que receba uma array com 11 números e retorne um número de telefone, respeitando parênteses, traços e espaços.

- [x] 12. Crie uma função de Condição de existência de um triângulo.

  Um triângulo é composto de três linhas: `lineA`, `lineB` e `lineC`. Crie uma função chamada `triangleCheck` que deverá receber as três linhas como parâmetro e retornar se é possível formar um triângulo com os valores apresentados de cada linha.

- [x] 13. Crie uma função de boas vindas ao Bar da Trybe!

  Segundo as regras desse bar, a cada bebida deve-se beber um copo de água para que não se tenha ressaca.
  
  Crie a função `hydrate` que recebe uma string, e retorne a sugestão de quantos copos de água você deve beber. Exemplos:
  
  ```js
  String recebida:
    "1 cerveja"
  String retornada:
    "1 copo de água"
  ``` 
  ```js
  String recebida:
    "1 cachaça, 5 cervejas e 1 copo de vinho"
  String retornada:
    "7 copos de água"
  ``` 
  ```js
  String recebida:
    "1 cachaça, 5 cervejas e 1 copo de vinho"
  String retornada:
    "7 copos de água"
  ``` 

##

<div align="center">
  <img src="https://shields.io/github/repo-size/lramos33/project-playground-functions">
  <img src="https://shields.io/github/languages/top/lramos33/project-playground-functions">
  <img src="https://shields.io/github/last-commit/lramos33/project-playground-functions">
</div>
