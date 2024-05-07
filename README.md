# Curso HTML e CSS Básico - Origamid

### :pencil2: Introdução

### 1. TAG

As tag's (etiquetas) servem para marcarmos o conteúdo no HTML. Geralmente abrimos <a> e fechamos </a> após o conteúdo. Case insensitive, mas é boa prática escrever com minúsculas <html>.

### 2. Atributo

```js
<a href="https://wwww.google.com">Google</a>
```

### 3. Conteúdo

As tags servem para inserirmos conteúdos como textos, imagens, vídeos e outros. Além da dar informações para o browser como o título do site, linguagem e outras.

### 4. Semântica

Dar sentido ao conteúdo, a escrita de um documento semântico beneficia principalmente leitores de tela (acessibilidade) e leitores de códigos (robôs como o do Google).

### 5. Interação com CSS e Javascript

Através das marcações das tags que conseguimos selecionar elementos para mudarmos o seu estilo ou comportamento.

### 6. Link Caminhos

**Absoluto**

```js
<a href="https://www.origamid.com/cursos/">Origamid Cursos</a>
```

Usado para arquivos externos ao nosso site.

**Relativo**
<a href="/produtos/bicicletas.html">Bicicletas</a>
Usado para arquivos internos do site.

### Links

**link**

- Cria uma relação entre um documento HTML e um arquivo de estilo CSS.

**rel**

- Define o tipo de arquivo (stylesheet para CSS). É possível linkar outros também como favicons.

**href**

- Define o caminho do arquivo.

```js
<link rel="stylesheet" href="/style.css" />
```

Exemplo

```js
a {
  color: black;
  text-decoration: none;
}
```

<!-- bloco css | propriedade | valor>
