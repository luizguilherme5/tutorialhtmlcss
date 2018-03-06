# Dojo de HTML/CSS | Uma introdução ao Web Development

## O que é o HTML?
HTML é a sigla para 'Hyper Text Markup Language' e é utilizado para descrever a estrutura de páginas web, utilizando uma linguagem de marcação. O HTML não é uma linguagem de programação e os elementos dele são  como blocos utilizados para criação de páginas. Cada elemento HTML é representado por uma tag e cada tag marca partes de página, como o cabeçalho, um parágrafo ou uma tabela.


### Exemplo
```
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
    </body>
</html>
```

### Explicação do exemplo
```
<!DOCTYPE> declara que o documento se trata de um HTML5
<html> é o que declara a raiz de uma página HTML
<head> contém meta informações sobre o documento
<title> especifica um título para um documento
<body> contém todo conteúdo visível na página
<h1> define um título grande
<p> defineum parágrafo
```

### Tags HTML
Toda tag no HTML é indicada por dois simbolos de 'maior e menor'. A maioria das tags é aberta e fechada, sendo a abertura sendo feita com ```<nomedatag>``` e o fechamento com ```</nomedatag>```

```
<nomedatag>Conteúdo que será mostrado</nomedatag>
```

#### Tags principais
```
* <html>
* <head>
* <title>
* <body>
* <h1> até <h6>
* <p>
* <br>
* <hr>
* <button>
* <form>
* <img>
* <a>
* <nav>
* <ul>
* <ol>
* <table>
* <style>
* <div>
* <header>
* <footer>
* <script>
* <!-- comentário -->
```

## Prática de HTML

## O que é CSS?
CSS é uma sigla para Cascading Style Sheets e ele funciona para descrever como os elementos HTML serão mostrados na tela. CSS salva muito seu tempo, pois você pode controlar como diversas páginas web funcionam de uma vez. Folhas de estilo externas são armazenadas em arquivos .css

## CSS resolve problemas
HTML <strong>NUNCA</strong> serviu para formatar uma página web e sim para descrever o comportamento de uma página. Tags como ```<font>``` foram adicionadas no HTML3 e isso se mostrou um pesadelo para os desenvolvedores do passado, então a W3C criou o CSS para formatar as páginas e tirar toda essa função do HTML.

## Sintaxe do CSS
Um conjunto de regras CSS consiste de um seletor e um bloco de declaração:

![Imagem da sintaxe](https://www.w3schools.com/css/selector.gif)

## Propriedades principais
```
* font-family
* font-size
* font-weight
* color
* background-color
* padding
* margin
* border
* width
* height
```

### Exemplo de uma tag de estilo no HTML
```
<head>
    <style>
        p {
            color: red;
            text-align: center;
        }
    </style>
</head>
```

### Exemplo de um estilo num elemento HTML
```
<h1 style="color:blue;">
    Esse é um título azul
</h1>
```

### Exemplo de um arquivo .css externo
```
/* Esse é um comentário num CSS*/
    p{
        color: white;    
    }

    h2 {
        font-size: 12px;
        font-weight: bold;
    }

    a {
        color: blue;
    }
```

## Prática de CSS
