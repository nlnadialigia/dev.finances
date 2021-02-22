<p align="center">
  <img src="./assets/logo.png" width=500>
</p>

---

<p align="center">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/nlnadialigia/dev.finances?color=822659&style=flat-square"/>

  <img alt="Repo size" src="https://img.shields.io/github/repo-size/nlnadialigia/dev.finances?color=822659"/>
   
  <a href="./license.md">
  <img alt="License" src="https://img.shields.io/static/v1?label=licence&message=MIT&color=822659"/>
  </a>
</p>

<p align="center">
  <a href="#-information_source-sobre">Sobre</a> •
  <a href="#-open_file_folder-aulas">Aulas</a> • 
  <a href="#-woman_office_worker-autora">Autora</a> • 
  <a href="#-pencil-licença">Licença</a>
</p>
<br>

# ℹ️ Sobre

Módulo da plataforma Discover, com os fundamento do javascript.

<br>

# 📂 Aulas

## 📌 Introdução

- Linguagem de programação que roda no navegador do usuário (front-end) ou no computador (back-end).

- Pode-se criar aplicações para web, mobile, desktop utilizando javascript.

<br>

## 📌 Tipos de dados

### 📚 String

- Cadeia de caracteres
- `""` => aspas duplas
- `''` => aspas simples
- `` => template literals ou template strings
<br>

### 📚 Number

- inteiros => 33
- reais - float => 12.5
- NaN => Not a Number
- Infinity => infinitivo

<br>

### 📚 Boolean

- somente 2 valores:
  - `true` => verdadeiro
  - `false` => falso

<br>

### 📚 Undefined vs null

**undefined** => indefinido, não existe

**null** => nulo
- objeto que não possui nada dentro
- diferente de indefinido

<br>

### 📚 Object

- Objeto
- Propriedades / Atributos
- Funcionalidades / Métodos

{propriedade: "valor"}

<br>

### 📚 Array

- uma lista
- agrupamento de dado

["Mayk", 36]

<br>

## 📌 Variáveis

### 📚 Conhecendo as variáveis

- [Exemplos](./variavel.html)

- nomes simbólico para receber algum valor
- atalhos de código
- identificadores
- 3 palavras reservadas para criar uma variável:
  - var
  - let
  - const => não pode mudar o seu valor durante a aplicação.

<br>

### 📚 Tipos dinâmicos

- [Exemplos](./variavel.html)

- O JS é uma linguagem fracamente tipada e dinâmica.
- Variáveis não precisam ter um tipo previamente definido
- Podemos mudar o conteúdo da variável.

<br>

### 📚 Scope e var

- [Exemplos](./scope.html)

- *scope* => determina a visibilidade de alguma variável no JS

- *block statement*
  ```js
  {
    //aqui dentro é um bloco que se pode colocar qualquer códio
  }
  ```

  - o bloco também criará um novo escopo, chamado `block-scoped`

- ***var*** => é global e poderá funcionar fora de um escopo de bloco. 
```js
console.log('> existe y antes do bloco?', y);
// Resposta: undefined

{
  var y = 33
}

console.log('> existe y depois do bloco?', y);
// Resposta: 33
```

<br>

### 📚 Scope let e const

- [Exemplos](./scope.html)

- const e let são locais e só funcionam no escopo onde foram criadas.
```js
console.log('> existe y antes do bloco?', a);

{
  let a = 33
}

console.log('> existe y depois do bloco?', a);
```
- **Resposta dos 2 consoles fora do escopo:** *Uncaught ReferenceError: a is not defined at scope.html*

<br>

### 📚 Nomeando variáveis

- JS é case-sensitve (sensível ao caso)
- JS aceita a cadeia de caracteres Unicode

- **Posso**
  * Iniciar com esses caracteres especiais: `$ _`
  * Iniciar com letras
  * Colocar acentos
  * Letras maísuculas e minúsculas fazem diferença

- **Não Posso**
  * Iniciar com números
  * Colocar espaços vazios no nome

- **Ideal**
  * Criar nomes que fazem sentido
  * Que explique o que a variável é ou faz
  * camelCase
  * snake_case
  * Escrever em inglês

<br>

<!-- 
## 📌 Praticando e avançando

### 📚 Declaration assignment var



<br>

### 📚 Agrupando declarações



<br>

### 📚 Concatenando e interpolando variáveis



<br>

### 📚 Objects



<br>

### 📚 Arrays



<br>

### 📚 Exercícios



<br>

## 📌 Funções

### 📚 Functions



<br>

### 📚 Argumentos e parâmetros



<br>

### 📚 Retornando valores dentro da função



<br>

### 📚 Outra maneira de entender funções



<br>

### 📚 Function scope



<br>

### 📚 Function Hoisting



<br>

### 📚 Arrow function



<br>

### 📚 Callback function



<br>

### 📚 Funções construtoras



<br>


## 📌 Manipulando dados

### 📚 Prototype



<br>

### 📚 Type conversion coersion



<br>

### 📚 Strings em números



<br>

### 📚 Contando caracteres e digitos



<br>

### 📚 Casas decimais



<br>

### 📚 Maiúsculas e minúsculas



<br>

### 📚 Encontrando palavras em frases



<br>

### 📚 Separando strings



<br>

### 📚 Criando array com construtor



<br>

### 📚 Elementos do Array



<br>

### 📚 Strings para arrays



<br>

### 📚 Manipulando arrays



<br>

## 📌 Expressões e Operadores

### 📚 Expressões e operadores



<br>

### 📚 New



<br>

### 📚 Typeof delete



<br>

### 📚 Operadores aritméticos



<br>

### 📚 Grouping operator



<br>

### 📚 Operadores de comparação



<br>

### 📚 Operadores de atribuição



<br>

### 📚 Operadores lógicos



<br>

### 📚 Operador condicional ternário



<br>

### 📚 Operadores para string



<br>

### 📚 Falsy e truthy



<br>

### 📚 Precedência dos operadores



<br>


## 📌 Condicionais e controle de fluxo

### 📚 Controle de fluxo da aplicação



<br>

### 📚 If e Else



<br>

### 📚 Switch



<br>

### 📚 Throw e Try/Catch



<br>

## 📌 Estruturas de repetição

### 📚 For



<br>

### 📚 While



<br>

### 📚 For of



<br>

### 📚 For in



<br>

## 📌 Consolidando com exercícios

### 📚 Praticar para aperfeiçoar



<br>

### 📚 Sistema de notas escolares



<br>

### 📚 Fluxo de caixa familiar



<br>

### 📚 Celsius to Fahrenheit



<br>

### 📚 Buscando e encontrando dados em Array



<br> -->

<br><br>

# 👩‍💼 Autora
<img style="border-radius: 50%" src="../../assets/picture.jpg" width="100px;" alt="Picture"/>
<p><b>Nádia Ligia</b></p>

[![Linkedin Badge](https://img.shields.io/badge/-nlnadialigia-822659?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nlnadialigia/)](https://www.linkedin.com/in/nlnadialigia/) 
[![Gmail Badge](https://img.shields.io/badge/-nlnadialigia@gmail.com-822659?style=flat&logo=Gmail&logoColor=white&link=mailto:nlnadialigia@gmail.com)](mailto:nlnadialigia@gmail.com)

<br>

# 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../../LICENSE) para mais detalhes.
