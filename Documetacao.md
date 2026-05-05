
# 📘 Documentação Web (HTML, CSS, JavaScript e Cache)

----------

## 🧱 HTML

Item

O que é

O que faz

HTML

Linguagem de marcação

Estrutura páginas web

`<html>`

Elemento raiz

Envolve todo o documento

`<head>`

Cabeçalho

Contém metadados

`<body>`

Corpo

Exibe conteúdo visível

`<h1>`

Título

Define títulos

`<p>`

Parágrafo

Exibe textos

`<a>`

Link

Navegação

`<img>`

Imagem

Exibe imagens

Semântica

Tags com significado

Melhora SEO e acessibilidade

### 🔧 Exemplo prático

```html
<!DOCTYPE html>
<html>
<head>
  <title>Exemplo</title>
</head>
<body>
  <h1>Meu site</h1>
  <p>Bem-vindo!</p>
  <a href="https://google.com">Ir para o Google</a>
</body>
</html>

```

### 🔧 Exemplo 2

```html
<!-- Estrutura semântica básica -->
<header>
  <h1>Logo</h1> <!-- Título principal -->
</header>
<main>
  <section>
    <p>Conteúdo aqui</p> <!-- Conteúdo principal -->
  </section>
</main>
<footer>
  <p>Rodapé</p> <!-- Informações finais -->
</footer>

```

### 🔧 Exemplo 3

```html
<!-- Formulário simples -->
<form>
  <input type="text" placeholder="Digite seu nome"> <!-- Campo texto -->
  <button type="submit">Enviar</button> <!-- Botão envio -->
</form>

```

### 🔧 Exemplo 4 (Tabela simples)

```html
<!-- Tabela básica -->
<table border="1"> <!-- cria tabela com borda -->
  <tr> <!-- linha -->
    <th>Nome</th> <!-- cabeçalho -->
    <th>Idade</th>
  </tr>
  <tr>
    <td>João</td> <!-- célula -->
    <td>25</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>30</td>
  </tr>
</table>

```

### 🔧 Exemplo 5 (Tabela com thead/tbody)

```html
<!-- Tabela mais estruturada -->
<table>
  <thead> <!-- cabeçalho da tabela -->
    <tr>
      <th>Produto</th>
      <th>Preço</th>
    </tr>
  </thead>
  <tbody> <!-- corpo da tabela -->
    <tr>
      <td>Mouse</td>
      <td>R$ 50</td>
    </tr>
    <tr>
      <td>Teclado</td>
      <td>R$ 120</td>
    </tr>
  </tbody>
</table>

```

------|--------|-----------|  
| HTML | Linguagem de marcação | Estrutura páginas web |  
| `<html>` | Elemento raiz | Envolve todo o documento |  
| `<head>` | Cabeçalho | Contém metadados |  
| `<body>` | Corpo | Exibe conteúdo visível |  
| `<h1>` | Título | Define títulos |  
| `<p>` | Parágrafo | Exibe textos |  
| `<a>` | Link | Navegação |  
| `<img>` | Imagem | Exibe imagens |  
| Semântica | Tags com significado | Melhora SEO e acessibilidade |

### 🔧 Exemplo prático

```html
<!DOCTYPE html>
<html>
<head>
  <title>Exemplo</title>
</head>
<body>
  <h1>Meu site</h1>
  <p>Bem-vindo!</p>
  <a href="https://google.com">Ir para o Google</a>
</body>
</html>

```

### 🔧 Exemplo 2

```html
<!-- Estrutura semântica básica -->
<header>
  <h1>Logo</h1> <!-- Título principal -->
</header>
<main>
  <section>
    <p>Conteúdo aqui</p> <!-- Conteúdo principal -->
  </section>
</main>
<footer>
  <p>Rodapé</p> <!-- Informações finais -->
</footer>

```

### 🔧 Exemplo 3

```html
<!-- Formulário simples -->
<form>
  <input type="text" placeholder="Digite seu nome"> <!-- Campo texto -->
  <button type="submit">Enviar</button> <!-- Botão envio -->
</form>

```

----------

## 🎨 CSS

Item

O que é

O que faz

CSS

Linguagem de estilo

Define aparência

Seletores

Identificadores

Aplicam estilos

Propriedades

Regras

Definem cores, tamanhos

Box Model

Modelo de caixa

Controla espaçamento

Flexbox

Layout 1D

Organiza elementos

Grid

Layout 2D

Layout avançado

Media Query

Regra condicional

Responsividade

### 🔧 Exemplo prático

```css
body {
  background-color: #eee; /* cor de fundo */
}

h1 {
  color: blue; /* cor do texto */
}

```

### 🔧 Exemplo 2 (Inline)

```html
<!-- CSS direto no elemento -->
<h1 style="color: red;">Título vermelho</h1> <!-- aplica estilo diretamente -->

```

### 🔧 Exemplo 3 (Interno)

```html
<!-- CSS dentro do HTML -->
<head>
  <style>
    h1 {
      color: green; /* define cor do título */
    }
  </style>
</head>

```

### 🔧 Exemplo 4 (Externo)

```html
<!-- HTML chamando arquivo CSS -->
<head>
  <link rel="stylesheet" href="style.css"> <!-- importa CSS externo -->
</head>

```

```css
/* arquivo style.css */
h1 {
  color: purple; /* estiliza título */
}

```

------|--------|-----------|  
| CSS | Linguagem de estilo | Define aparência |  
| Seletores | Identificadores | Aplicam estilos |  
| Propriedades | Regras | Definem cores, tamanhos |  
| Box Model | Modelo de caixa | Controla espaçamento |  
| Flexbox | Layout 1D | Organiza elementos |  
| Grid | Layout 2D | Layout avançado |  
| Media Query | Regra condicional | Responsividade |

### 🔧 Exemplo prático

```css
body {
  background-color: #eee; /* cor de fundo */
}

h1 {
  color: blue; /* cor do texto */
}

```

### 🔧 Exemplo 2

```css
/* Flexbox para centralizar */
.container {
  display: flex; /* ativa flex */
  justify-content: center; /* centraliza horizontal */
  align-items: center; /* centraliza vertical */
}

```

### 🔧 Exemplo 3

```css
/* Responsividade */
@media (max-width: 600px) {
  body {
    font-size: 14px; /* reduz fonte em telas pequenas */
  }
}

```

----------

## ⚙️ JavaScript

Item

O que é

O que faz

JavaScript

Linguagem de programação

Adiciona lógica

Variáveis

Armazenamento

Guardam dados

Funções

Blocos de código

Executam ações

Eventos

Interações

Respondem ao usuário

DOM

Estrutura da página

Permite manipulação

Fetch

API nativa

Faz requisições HTTP

Async/Await

Assíncrono

Controla requisições

### 🔧 Exemplo prático

```javascript
function clicar() {
  document.getElementById("msg").innerText = "Clicou!"; // altera texto
}

```

```html
<button onclick="clicar()">Clique</button>
<p id="msg"></p>

```

### 🔧 Exemplo 2

```javascript
// Soma simples
function soma(a, b) {
  return a + b; // retorna resultado
}

console.log(soma(2,3)); // imprime 5

```

### 🔧 Exemplo 3

```javascript
// Requisição API
async function carregar() {
  const res = await fetch('/api'); // chama API
  const dados = await res.json(); // converte JSON
  console.log(dados); // mostra dados
}

```

----------

## 💾 Cache

Item

O que é

O que faz

Cache

Armazenamento temporário

Melhora performance

Cache navegador

Local

Acelera carregamento

Cache servidor

Backend

Reduz processamento

CDN

Rede distribuída

Entrega conteúdo rápido

Cache-Control

Header HTTP

Define regras de cache

ETag

Identificador

Valida conteúdo em cache

### 🔧 Exemplo prático

```http
Cache-Control: max-age=3600

```

➡️ Guarda por 1 hora

### 🔧 Exemplo 2

```http
Cache-Control: no-cache

```

➡️ Sempre valida com o servidor

### 🔧 Exemplo 3

```http
ETag: "abc123"

```

➡️ Identifica versão do conteúdo
