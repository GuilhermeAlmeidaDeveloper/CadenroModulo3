DOM significa Document Object Model.

É uma maneira de manipular elementos do HTML e suas estilizações, para tornar os sites interativos utilizando lógica de programação.

API significa, interface de Programação de Aplicações.

As API'S permitem trabalhar com um conjunto de rotinas e padrões estabelecidos por um software para utilização de suas funcionalidades.

Apesar da maioria das vezes relacionarmos a DOM ao javascript, nao necessariamente os dois estão atrelados, segundo a documentação oficial, é possível manipular DOM com Python por exemplo.

Podemos escrever javascript na tag <script> e importar arquivos externos.

Os códigos de JS, devem ser preferencialmente importados/colocados no final do HTML, pois a leitura do tipo de arquivo é feita de cima para baixo.

# Seleção de elementos;

Existem diversas maneiras de selecionar um elemento HTML usando a DOM.

Nesta aula veremos apenas a chamada querySelector, que permite selecionar elementos usando a mesma logica de seletores do CSS.

document.querySelector ('.area--header')

<div class = 'area-header'> teste </div>

Para selecionar todos os elementos do mesmo tipo de uma vez, utilizamos o document.querySelectorAll ('h1')

Teste


# Eventos em JS.

São maneiras do JS observar a interação do usuário com elementos da DOM.

Quais os eventos mais utilizados?

-Click
-Chance
-Mouseover
-KeyPress
-KeyDown
-KeyUp
-Focus

Priorizar escrever o evento dentro do arquivo JS.

No HTML:

<div class= 'box'> 
</div>

No JS:

const box = document.querySelector ('.box')

function observerMouseover (){
    console.log ('mouse foi passado por cima')
}

box.addEventListener ('mouseover', observerMouseOver).

EventListener  = mouseover 
EventHandler = observerMouseOver

Podemos remover o evento através do removeEventListener
