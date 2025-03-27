<h1 align="center" style="font-weight: bold;">Nome do projeto 💻</h1>

<p align="center">
 <a href="#tech">Tecnologias</a> •
 <a href="#started">Começando</a> •
 <a href="#routes">Endpoints da API</a> •
 <a href="#structure">Estrurtura do projeto</a> •
 <a href="#colab">Colaboradores</a> •
 <a href="#contribute">Contribuir</a>
</p>

<p align="center"> 
 <b>Descrição simples do que seu projeto faz ou como usá-lo.</b>
</p>


<h2 id="technologies">💻 Tecnologias</h2>

- Lista completa de todas as tecnologias usadas.
- Python
- Pandas
- SQL
- jupyter


<h2 id="started">🚀 Começando</h2>

Aqui você descreve como executar seu projeto localmente.


### Pré-requisitos

Aqui você lista todos os pré-requisitos necessários para rodar seu projeto. Por exemplo:
- [NodeJS](https://nodejs.org/pt)
- [java 8](https://www.java.com/pt-BR/)


### Cloning

Como clonar seu projeto:

```bash
git clone url-do-seu-projeto-no-github
```


### Config .env variables

Exemplo de arquivo `.env.example` com suas credencias para ser usado no `.env`.

```yaml
NODE_AWS_REGION=sua-regiao
NODE_AWS_KEY_ID={seu-id-aws}
NODE_AWS_SECRET={sua-senha-aws}
```


### Iniciando

Como iniciar seu projeto:

```bash
cd nome-do-projeto
npm comando-para-executar
```

<h2 id="routes">📍 Endpoints da API</h2>

Aqui você pode listar as principais rotas da sua API e quais são os corpos de requisição esperados.
​
| route               | description                                          
|----------------------|-----------------------------------------------------
| <kbd>GET /authenticate</kbd>     | Recupera informações do usuário. <a href="#get-auth-detail">Veja mais!</a>
| <kbd>POST /authenticate</kbd>     | Autentica o usuário na API. <a href="#post-auth-detail">Veja mais!</a>


<h3 id="get-auth-detail">GET /authenticate</h3>

**RESPOSTA**
```json
{
  "nome": "Guilherme Carvalho Barbosa",
  "idade": 24,
  "email": "meu-email@gmail.com"
}
```


<h3 id="post-auth-detail">POST /authenticate</h3>

**REQUISIÇÃO**
```json
{
  "usuario": "GuiCarBar",
  "senha": "1234567"
}
```


**RESPOSTA**
```json
{
  "token": "OwoMRHsaQwyAgVoc3OXmL1JhMVUYXGGBbCTK0GBgiYitwQwjf0gVoBmkbuyy0pSi"
}
```


<h2 id="structure">📂 Estrutura do Projeto</h2>

- Aqui voce vai colocar a estrutura do projeto com seus arquivos ...

```bash
📦 NomeDoProjeto
├── 📁 src
│   ├── 📄 index.js
│   ├── 📄 app.js
│   └── 📄 config.js
├── 📄 README.md
├── 📄 package.json
└── 📄 .gitignore
```


<h2 id="colab">🤝 Colaboradores</h2>

Um agradecimento especial a todas as pessoas que contribuíram para este projeto.

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Lc3_2018_%28263682303%29_%28cropped%29.jpeg/220px-Lc3_2018_%28263682303%29_%28cropped%29.jpeg" width="100px;" alt="Linus Torvalds"/><br>
        <sub>
          <b>Linus Torvalds</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Robert_C._Martin_surrounded_by_computers_%28cropped%29.jpg/640px-Robert_C._Martin_surrounded_by_computers_%28cropped%29.jpg" width="100px;" alt="Robert C. Martin"/><br>
        <sub>
          <b>Robert C. Martin</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/14/James_Gosling_2008.jpg" width="100px;" alt="James Gosling"/><br>
        <sub>
          <b>James Gosling</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/61896274?v=4" width="100px;" alt="Fernanda Kipper Profile Picture"/><br>
        <sub>
          <b>Fernanda Kipper</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


<h2 id="contribute">📫 Contribuir</h2>

Aqui você explicará como outros desenvolvedores podem contribuir para o seu projeto. Por exemplo, explicando como criar suas branches, quais padrões seguir e como abrir um pull request.

1. `git clone https://github.com/Seu-Usuario/Nome-so-seu-Projeto.git`
2. `git checkout -b feature/Nome-da-branch`
3. Siga os padrões de commits.
4. Abra um Pull Request explicando o problema resolvido ou funcionalidade criada. Se houver, adicione capturas de tela das modificações visuais e aguarde a revisão!


### Documentações que podem ajudar

[📝 Como criar um Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)

[💾 Padrão de commits](https://github.com/iuricode/padroes-de-commits)


## ✨ Créditos e Inspiração 

Se você se inspirou ou se baseou em outro projeto, este é um ótimo espaço para mencionar e dar os devidos créditos.


## 📜 Licença

Este projeto está sob a licença [MIT](../../LICENSE) License.