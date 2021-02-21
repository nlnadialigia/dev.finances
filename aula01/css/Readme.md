<p align="center"><img src="./assets/logo.png"></p>

---

<p align="center">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/nlnadialigia/dev.finances?color=822659&style=flat-square"/>

  <img alt="Repo size" src="https://img.shields.io/github/repo-size/nlnadialigia/dev.finances?color=822659"/>
   
  <a href="./license.md">
  <img alt="License" src="https://img.shields.io/static/v1?label=licence&message=MIT&color=822659"/>
  </a>
</p>

<p align="center">
  <a href="#-information_source-sobre-a-aula">Sobre</a> •
  <a href="#-open_file_folder-orientações">Orientações</a> • 
  <a href="#-woman_office_worker-autora">Autora</a> • 
  <a href="#-pencil-licença">Licença</a>
</p>
<br>

# ℹ️ Sobre a aula

Estudo de seletores, combinadores, pseudo-classes e pseudo-elementos em CSS.

<br>

# 📂 orientações

## 📌 Selectors and Combinators
<br>

### 📚 seletores
- Conecta um elemento HTML com o CSS a fim de alterar o elemento.

#### ▶️ Tipos

* `Element selector` => todos os elmentos HTML
* `ID Selector` => um elmento que tenha um atributo `id`. **Cada id deverá ser único**
* `Class Selector` => os elementos que contenha um atributo `class`. **Podemos ter uma ou mais classes**
* `Attribute selector` => um elmento que tenha um atributo específico.
* `Pseudo-class selector` => elementos em um estado específico.

### ▶️ Múltiplos

- Poderão ser selecionados múltiplos elmentos e aplicar alguma regra css para todos eles.

- É utilizada a vírgula para fazer a separação

```css
h1, p, a {
  color: red;
}
```
<br>

### 📚 combinators
- Combinadores, pois eles trabalham para buscar e combinar seletores a fim de aplicar uma estilização.

### ▶️ Descendant combinator
- Identificado por um espaço entre os seletores.
- Busca um elmento dentro de outro

```cs
body aritcle h2
```
<br>

### 📚 combinators-child
- Identificado pelo sinal `>` entre dois seletores
- Seleciona domente o elemento que é filho direto do pai
- Elementos depois do filho direto serão desconsiderados

```css
body > ul > li
```
<br>

### 📚 combinators-siblings

#### ▶️ Adjacent sibling combinator
- Identificado pelo sinal de `+` entre dois seletores
- Seleciona somente o elmento do lado direito que é irmão direto na hierarquia

```css
h1 + p
```
<br>

#### ▶️ General sibling combinator
- Identificado pelo sinal de `~` entre dois seletores
- Seleciona todos os elmentos irmãos
```css
h1 ~ p
```
<br>

### 📚 utilizando-combinators

```css
ul > li[class="red"]
```

#### ▶️ Dicas
- seletores muito específicos tendem a causar dificuldades no reuso das regras de estilização dos elementos
- Muitas vezes, um simples uso de classes, torna o trabalho mais eficiente.
<br>

## 📌 Pseudo-classes
- É um tipo de seletor que irá selecionar um elmento que estiver em um estado específico.

- *Exemplo:* é o primeiro elmemento dentro de uma caixa, ou, o elmento está com o ponteiro do mouse em cima dele.

- Pseudo-classes começam com 2 pontos seguido do nome da pseudo class.
`:pseudo-class-name`
<br>

### 📚 first-child
- é o primeiro filho dentro do seletor. 

```css
ul li:first-child{
  font-weight: bold;
}
```
 
<br>

### 📚 nth-of-type
- pegar dos tipos o (n) elemento.

```css
article p:nth-of-type(1){
  font-weight: bold;
  font-size: 18px;
}
```
<br>

### 📚 nth-child
- os filhos do principal
```css
article p:nth-child(2){
  font-weight: bold;
  font-size: 18px;
}
```
<br>

### 📚 nth-child-odd-even
- even => números pares
- odd => números ímpares
```css
ul li:nth-child(odd) {
  background-color: blue;
}
```
<br>

### 📚 hover-focus
- hover => mouse em cima
- focus => campos de input => geralmente altera a borda quando o input está em foco no padrão.
```css
a:hover {
  color: red;
}

input:focus {
  border: 2px solid green;
}
```
<br>

### 📚 disabled-required
- utilização do atributo para atribuir estilização ao campo.

```css

input:required {
  background-color: goldenrod;
}

input:disabled {
  background-color: blue;
}
```
<br>

### 📚 [Referência: ](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Pseudo-classes)

<br>

## 📌 Pseudo-elements
- Adição de elementos HTML pelo próprio css.
`::pseudo-element-name`

▶️ ::before
▶️ ::after
▶️ ::first-line

### 📚 ::[Referência](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

<br>

# 👩‍💼 Autora
<img style="border-radius: 50%" src="../../assets/picture.jpg" width="100px;" alt="Picture"/>
<p><b>Nádia Ligia</b></p>

[![Linkedin Badge](https://img.shields.io/badge/-nlnadialigia-822659?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nlnadialigia/)](https://www.linkedin.com/in/nlnadialigia/) 
[![Gmail Badge](https://img.shields.io/badge/-nlnadialigia@gmail.com-822659?style=flat&logo=Gmail&logoColor=white&link=mailto:nlnadialigia@gmail.com)](mailto:nlnadialigia@gmail.com)

<br>

# 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../../LICENSE) para mais detalhes.
