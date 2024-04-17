# JavaScript-3

## DOM
- Document Object Model
- Estrutura de um arquivo na Web
- Representa documentos HTML ou XML
- Interface de programação
- NÃO é uma linguagem de programação
- É essencial para o JS entender o modelo de paginas web

## Para que serve ?
- Alterar a estrutura
- Alterar o estilo
- Alterar o conteúdo

## Como ?
- Disponibiblidade API (Application Programming Interface)
- Rotinas e padrões estabelecidos
- Métodos (funções)
- Árvore de elementos
- Seletores
- Objetos (nós / nodes)

<html>
     <head></head>
     <body></body>
</html>
...

## Exemplo 
objeto = {
   html : {
       head : {},
       body : {
          h1 : {

          }
       }
   }
}
...


## DOM X JS
- O DOM pode ser usado por outras linguagens
- Sem o DOM o JS não teria noção da página

### Vantagens de usar a JavaScript
- Código é executado por navegadores
- Tornar as páginas dinâmicas
- Evitar Requisições desncessárias (perfomance)
- SPA(Single Page Applications)
- Reagir rapidamente a ações dos usuários

### Desvantagens de usar o JavaScript 
- Código é executado por navegadores
- O conteúdo NÃO fica visível para indexadores de busca
- Alterações em tempo de execução não ficam salvas no documento


### Exemplos
Selecione o objeto e disposinibiliza (métodos / funções).callback

- document.getElementById(id)
- document.getElementsByTagName('div')
- document.createElement('div')
- parentNode.appendChild(node) //html.appendChild('body')
- element.innerHTML
- element.style
- element.setAttribute('name')
- element.getAttribute('name')
- element.addEventListener()
- window.location
- window.onload 
- console.log()
- window.scrollTo(x, y)

### Referências 
- DOM : https://dom.spec.whatwg.org/
- Tecnologias JS: https://developer.mozzila.org/pt-BR/docs/Web/JavaScript/JavaScript_technologies_overview
- Motores de execução: http://pt.wikipedia.org/wiki/Lista_de_motores_de_renderiza%C3%A7%C3%A3o
