# Mudança Aleatória de Cor de Fundo

## Descrição

Este projeto é uma aplicação web simples que altera aleatoriamente a cor de fundo da página sempre que um botão é clicado. As cores de fundo são escolhidas a partir de um conjunto pré-definido de cores escuras. O valor hexadecimal da cor de fundo atual também é exibido na página.

## Funcionalidades
- Exibe a cor de fundo atual no formato de código hexadecimal.
- Altera a cor de fundo para um valor aleatório a partir de uma lista de cores escuras pré-definidas.
- Botão estiloso com efeito de hover que aciona a mudança de cor de fundo.

## Tecnologias Utilizadas
- **HTML**: Estrutura e conteúdo da página.
- **CSS**: Estilização da página e seus elementos.
- **JavaScript**: Funcionalidade para alterar a cor de fundo aleatoriamente quando o botão é clicado.

## Estrutura de Arquivos
- `index.html`: Contém a estrutura da página.
- `styles.css`: Contém os estilos para a página e o botão.
- `script.js`: JavaScript que lida com a funcionalidade de mudança da cor de fundo.

## Instalação
1. Faça o download ou clone o repositório para o seu computador local.
2. Abra o arquivo `index.html` em qualquer navegador moderno.

## Como Funciona

### HTML

O arquivo `index.html` define a estrutura da página com:
- Um título `<h1>` que nomeia a página.
- Uma seção `<section>` que exibe a cor de fundo atual no formato hexadecimal.
- Um botão `<button>` que aciona a mudança da cor de fundo ao ser clicado.

### CSS

O arquivo `styles.css` estiliza a página ao:
- Definir a cor de fundo, cor do texto e o layout da página.
- Estilizar o botão, incluindo seu efeito de hover e transições de cor.

### JavaScript

O arquivo `script.js` contém a lógica para a mudança da cor de fundo:
- Um array pré-definido `darkColorsArr` contém uma lista de valores hexadecimais de cores escuras.
- A função `getRandomIndex()` gera um índice aleatório para selecionar uma cor do array.
- A função `changeBackgroundColor()` altera a cor de fundo e atualiza o código hexadecimal exibido na página quando o botão é clicado.

## Uso

- Clique no botão "Change Background Color" (Alterar Cor de Fundo) para mudar a cor de fundo da página para uma cor escura aleatória.
- O código hexadecimal da nova cor será exibido abaixo do título.

## Exemplo

- Cor de fundo inicial: `#110815`
- Após clicar no botão, a cor pode mudar para algo como `#2C3E50`, e o novo código hexadecimal será exibido.

