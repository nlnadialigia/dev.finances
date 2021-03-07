<p align="center"><img src="./assets/logo.png" width=200></p>
<h2 align="center">Aula 03</h2>

---
<p align="center">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/nlnadialigia/dev.finances?color=91091e&style=flat-square"/>

  <img alt="Repo size" src="https://img.shields.io/github/repo-size/nlnadialigia/dev.finances?color=91091e"/>
   
  <a href="./license.md">
  <img alt="License" src="https://img.shields.io/static/v1?label=licence&message=MIT&color=91091e"/>
  </a>
</p>

---

<p align="center">
  <a href="#-information_source-sobre-a-aula">Sobre</a> •
  <a href="#-open_file_folder-conteúdo">Conteúdo</a> • 
  <a href="#-woman_office_worker-autora">Autora</a> • 
  <a href="#-pencil-licença">Licença</a>
</p>
<br>

# ℹ️ Sobre a aula

Javascript

📌 Objetos<br>
📌 Tipos e estrutura de dados<br>
📌 If/else<br>
📌 Erros<br>
📌 Funcionalidades<br>
📌 Adicionar e remover transações<br>
📌 Calcular<br>
📌 Salvar no localStorage<br>

<br>

# 📂 Conteúdo

## 📚 Apresentação
<br>
<p align="center">
<img src="./assets/class03.gif" height=400>
</p>
<br>

## 📚 Pontos interessantes

Na criação das funcionalidades do formulário, cada funcionalidade será criada separadamente e depois incluída no `submit(event)`.
```js
  submit(event) {
    event.preventDefault();

    try {
      // verificar se todas as informações foram preenchidas
      Form.validateField();
      // formatar os dados para salvar
      const transaction = Form.formatValues();
      // salvar
      Transaction.add(transaction);
      // limpar os dados do formulário
      Form.clearFields();
      // fechar o modal
      Modal.close();
      // atualizar a aplicação => está incluso no Transaction.add 
      
    } catch (error) {
      alert(error.message);
    }
  }
};
```
<br>

## 📚 Tarefa 03: Assistir aos cursos/aulas
<br>

### 📌 Revisão
* [O guia estelar de JavaScript](https://app.rocketseat.com.br/node/o-guia-estelar-de-java-script)

### 📌 Assistir
- [O guia estelar de Git](https://app.rocketseat.com.br/node/o-guia-estelar-de-git)
- [O guia estelar de GitHub](https://app.rocketseat.com.br/node/o-guia-estelar-de-git-hub)
- [Pilotando com a DOM](https://app.rocketseat.com.br/node/pilotando-com-a-dom)
<br>

# 👩‍💼 Autora
<img style="border-radius: 50%" src="../assets/picture.jpg" width="100px;" alt="Picture"/>
<p><b>Nádia Ligia, desenvolvedora back-end em formação.</b></p>

<a href="https://www.linkedin.com/in/nlnadialigia/">
  <img alt="Linkedin" src="https://img.shields.io/badge/-Linkedin -91091e?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nlnadialigia/" />
</a>&nbsp;
<a href="mailto:nlnadialigia@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/-Email-91091e?style=flat&logo=Gmail&logoColor=white&link=mailto:nlnadialigia@gmail.com" />
</a>&nbsp;
<a href="https://www.nlnadialigia.com">
  <img alt="Homepage" src="https://img.shields.io/badge/-Homepage-91091e" />
</a>

<br><br>

# 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../LICENSE) para mais detalhes.