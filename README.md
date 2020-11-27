<h1 align="center">🚀 HTML 🚀</h1>

![Badge](/github/tag.png)

<div align="center">
  <img align="center" src="./github/atributos.png">
</div>

<br/>

<h4>Os atributos são usados para personalizar as tags, modificando sua estrutura ou funcionalidade. Portanto, os atributos são utilizados para atribuir uma classe ou id a um elemento. Esses são os principais, porém existe vários.</h4> <br/>

**class=”…“** – Atribui uma classe ao elemento (uma classe pode ser utilizada para um ou mais elementos); <br/><br/>
**id=”…“** – Atribui um id ao elemento (um id deve ser único, ou seja, atribuído a um único elemento);<br/> <br/>
**style=”…”** – Permite incluir elementos CSS (estilos) dentro da tag;<br/><br/>
**lang=”…”** – Define o idioma principal do elemento;<br/><br/>
**title=”…”** – Define o título do elemento;<br/><br/>
**alt=”…”** – Define um texto alternativo e, por isso, é muito utilizado em imagens, auxilia nas práticas de SEO;<br/><br/>
**hidden** – Oculta o elemento;<br/><br/>
**align=”…”** – Permite definir o padrão de alinhamento desse elemento, como por exemplo: right, center, left e justify;<br/><br/>
**width=”…”** – Define uma largura para o elemento;<br/><br/>
**height=”…”** – Define uma altura para o elemento.<br/> <br/>

<h1 style="color: aqua;">Tags</h1>

<div align="center">
  <img align="center" src="./github/coment.png">
</div>

<h2 style="color: rgb(240, 58, 164)">Comentário</h2> <br/>

Obs: Ele não será exibido em tela.

```bash
<!-- Escreva seu comentário -->
```

<h2 style="color: rgb(240, 58, 164)">DOCTYPE html</h2> <br/>

Utilizada para iniciar e indicar a versão do Html. <br/>
Por exemplo, Html:5

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
</body>
</html>
```

<h2 style="color: rgb(240, 58, 164)">Html</h2> <br/>

Todo conteúdo do código Html.

```bash
<html>
  <head></head>
  <body></body>
</html>
```

<h2 style="color: rgb(240, 58, 164)">Head</h2> <br/>

A tag head representa uma coleção de metadados para o documento onde não são exibidos no navegador. Metadados são, dados sobre os dados. E é utilizada para inserir informações do cabeçalho do documento, como título, links para css, links para favicons, links para fontes e outros metadados, como: Quem o escreveu, palavras-chave importantes que descrevem o documento etc.

```bash
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./styles.css" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap"
      rel="stylesheet"
    />
    <link rel="icon" type="image/png" sizes="16x16" href="./images/icon.png" />
    <title>Tags Html</title>
  </head>
```

<h2 style="color: rgb(240, 58, 164)">Title</h2> <br/>

Utilizada para inserir o título da página web (Guia).

```bash
<title>Escreva o Título</title>
```

<h2 style="color: rgb(240, 58, 164)">Meta</h2> <br/>

Os metadados contendo informações do documento.

```bash
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

<h2 style="color: rgb(240, 58, 164)">Link</h2> <br/>

Inclusão de outros documentos.

```bash
<link rel="stylesheet" href="./styles.css" />
<link rel="preconnect" href="https://fonts.gstatic.com" />
<link
  href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap"
  rel="stylesheet"
/>
<link rel="icon" type="image/png" sizes="16x16" href="./images/icon.png" />
```

<h2 style="color: rgb(240, 58, 164)">Body</h2> <br/>

Todo corpo do documento.

```bash
<body>
    <section>
      <div>
        <nav>
          <a href="#"></a>
        </nav>
      </div>
    </section>
    <footer></footer>
    <script src="scripts.js"></script>
</body>
```

<br/>

**Obs:** Todas as tags a seguir, poderão ser utilizadas dentro do body.

<h2 style="color: rgb(240, 58, 164)">Style</h2> <br/>

Estilização do conteúdo.

```bash
<h2 style="color: rgb(240, 58, 164)">Styles</h2>
```

<h2 style="color: rgb(240, 58, 164)">Script</h2> <br/>

Utilizado para colocar o contéudo de linguagem script.

```bash
<script src="scripts.js"></script>>
```

<h2 style="color: rgb(240, 58, 164)">P</h2> <br/>

Parágrafo.

```bash
<p>Escreva seu texto</p>
```

<h2 style="color: rgb(240, 58, 164)">A</h2> <br/>

O elemento <-a-> ou também chamado de elemnto âncora, é utilizado para a criação de links, e, com o atributo **href** cria-se um hiperligação nas páginas web, arquivos, endereços de emails, ligações na mesma página ou endereços na URL. Existem outros atributos, mas estes são os mais utilizados.

```bash
<a href="#" target="_blank" rel="noreferrer noopener"></a>
<a href="https://site.com">Website</a>
<a href="mailto:email@gmail.com">Email</a>
<a href="tel:+123456789">Phone</a>
```

<br/>

**href=""** – Utilizado para criar hiperligações entre páginas; <br/>
**mailto:** – Utilizado para inserir e-mails; <br/>
**tel:** – Utilizado para inserir números de telefone; <br/>
**target="\_blank"** – Utilizado para abrir uma nova aba; <br/>
**Obs:** Utilize **rel="noreferrer noopener"**, juntamente com o **\_blank**, para evitar "exploit". Usar target="\_blank" sem rel="noreferrer" ou rel="noopener" torna o site vulnerável a window.opener. <br/>

<h2 style="color: rgb(240, 58, 164)">Img</h2> <br/>

Utilizada para inserir imagens.

```bash
<img src="imgem/imagem.png" alt="logo" />
```

### Formatos de imagens suportados:

<ul>
    <li>JPEG</li>
    <li>GIFs</li>
    <li>PNG</li>
    <li>APNG</li>
    <li>SVG</li>
    <li>BMP</li>
    <li>BMP ICO</li>
    <li>PNG ICO</li>
</ul>

<h2 style="color: rgb(240, 58, 164)">Pre</h2> <br/>

É a tag utilizada para representar um texto pré-formatado. Um texto dentro desse elemento é exibido em uma fonte não proporcional da mesma maneira em que o texto original foi escrito no arquivo. Espaços em branco são mantidos no texto da mesma forma em que foi digitado.

```bash
<pre>
body {
  color: pink;
}
</pre>
```

<h2 style="color: rgb(240, 58, 164)">H1</h2> <br/>

Refere-se ao cabeçalho, onde varia de h1 à h6, sendo h1 o maior font-size (tamanho da letra) e h6 o menor.

```bash
<h1>Text</h1>
<h2>Text</h2>
<h3>Text</h3>
<h4>Text</h4>
<h5>Text</h5>
<h6>Text</h6>
```

<h3 style="color: aqua;">Estruturas</h3> <br/>

<h2 style="color: rgb(240, 58, 164)">Main</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Header</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Section</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Article</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Aside</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Nav</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Div</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Footer</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h3 style="color: aqua;">Formulários</h3> <br/>

<h2 style="color: rgb(240, 58, 164)">Form</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Input</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Textarea</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Select</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Option</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Label</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h3 style="color: aqua;">Tabelas</h3> <br/>

<h2 style="color: rgb(240, 58, 164)">Table</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Caption</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Tr</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Th</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">td</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h3 style="color: aqua;">Listas</h3> <br/>

<h2 style="color: rgb(240, 58, 164)">Ol</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Ul</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Li</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Menu</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Dir</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Dl</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Dt</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Dd</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h3 style="color: aqua;">Formatação</h3> <br/>

<h2 style="color: rgb(240, 58, 164)">B</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">I</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">U</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Strong</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<h2 style="color: rgb(240, 58, 164)">Em</h2> <br/>

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

<br/>

<h2>💡 Deseja contribuir com esse projeto?</h2> <br/>

### Faça um fork utilizando a linha de comando oficial do GitHub

```bash
$ gh repo fork DeboraZandonai/TagsHtml
```

### Clone o seu fork e e navegue até a pasta

```bash
$ git clone url-do-seu-fork && cd TagsHtml
```

### Crie uma branch com as suas features

```bash
$ git checkout -b minha-feature
```

### Faça um commit das suas alterações

```bash
$ git commit -m 'feat: suas alterações'
```

### Envie o código para a sua branch remota

```bash
$ git push origin minha-feature
```

Depois que a sua pull request for aceita você pode deletar a sua branch.

## 📝 Licença

Este projeto encontra-se sob a licença **MIT**. Para mais informações, acesse o arquivo **LICENSE**.

<h4 align=center>Made with ❤️ by <a href="https://www.linkedin.com/in/debora-zandonai-4ab092195/">Debora Zandonai</a></h4>
