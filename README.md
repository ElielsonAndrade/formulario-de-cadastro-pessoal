 Formulário de Cadastro Pessoal - Formação Tech

- [Formulário de Cadastro Pessoal - Formação Tech](#formulário-de-cadastro-pessoal---formação-tech)
    - [Autor](#autor)
    - [Objetivo](#objetivo)
    - [Ferramenta](#ferramenta)
    - [Linguagens](#linguagens)

### Autor:

- [Elielson Silva Andrade](https://github.com/ElielsonAndrade)
- **Idade**: 34 anos
- **Tipo de deficiência:** Visual. 

### Objetivo:

Desenvolver um *site* penqueno e acessível, como um formulário de cadastro pessoal com campos de preenchimento 
obrigatórios além de  validações e expressões regulares.  

### Ferramenta:

Visual Studio Code no Windows.

### Linguagens: 

- - HTML
- - CSS
- JavaScript

## Descrição do site

### HTML

Começa com um método de documentação para renderizar HTML – `<!DOCTYPE HTML>` e um método de HTML com uma etiqueta `lang` pegando a língua portuguesa do Brasil. Entrando na `head`, que é um método que provdiencia metadados, título (`<title`>), *links* dos ícones, das fontes, do CSS, do JavaScript e o estilo interno (`<style>`), começando com título, um metadado de renderização de caracteres e um metdado de autoria. 

Então no corpo, no qual há um cabeçalho (`<header>`) contendo um título de primeiro grau (`<h1>`) e parágrafos (`<p>`), e um conteúdo principal (`<main>`) contendo um formulário (`<form>`). No formulário, temos grupos (`<fieldset>`), dentro dos quais, temos legendas (`<legend`>) dos grupos, rótulos (`<label`>) e caixas de entradas (`<input>`) com um tipo (`type`), um identificador (`id`) e um nome (`name`) pegados pelos rótulos. Os tipos das caixas de entradas podem ser texto, número, telefone, e-mail, data, seleção de opções, seleção de escolha e senha. Também temos uma área de mensagem para escrever (`textarea`). No final, há dois botões (`input`) para enviar e limpar, contendo métodos em JavaScript para clicar as funções em JavaScript. 

### JavaScript

É um script interno. Nele, temos uma função que checa se nós quiseremos enviar e abre o diálogo para nos perguntar, senão cancelamos a janela, e outra função que informa que limparemos o formulário ao clicarmos naquele botão. 
