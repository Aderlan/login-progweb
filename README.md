# login-progweb
lista de exercício

1) O código abaixo, feito em HTML, possui um grave erro sintático. Assinale qual é esse erro e descreva o que precisa ser feito para corrigi-lo:
<!DOCTYPE html>
<!-- Página do Instituto de Computação -->
<html>
<head>
<title>Instituto de Computação</title>
</head>
<body>
<meta charset='UTF-8'>
<h1>Instituto de Computação</h1>
<img src='imagens/icomp.png' width='260' height='111' alt='IComp'>
<p>
O <strong>Instituto de Computação (Icomp)</strong> é um
instituto acadêmico da Universidade Federal do
Amazonas que atua no ensino, pesquisa e extensão.
</p>
</body>
<!-- Fim da Página -->
</html>

2) No código acima, usamos os atributos height e width para informar as dimensões da imagem imagens/icomp.png ao browser. Qual a importância desse procedimento, uma vez que o browser é capaz de identificar tais dimensões após o carregamento da imagem?
Importante procedimento:
Se não forem definidos os valores para width e height, a imagem será inserida com seu tamanho real.

3) Escreva um código HTML para gerar a página da figura abaixo:
<!DOCTYPE html>
<!-- Página do Instituto de Computação -->
<html>
<head>
	<meta charset="UTF-8">
	<title>Instituto de Computação</title>
</head>
<body>
	<h1>Instituto de Computação</h1>
	<table border="1">
		<caption>Professores do Grupo de Banco de Dados e Recuperação de Informação, do Instituto de Computação da UFAM</caption>
		<thead>
			<tr>
				<td colspan=3 style="text-align: center;">Professores do BRDI, UFAM</td>
			</tr>
			<td>Nome</td>
			<td>Cargo</td>
			<td>E-mail</td>
		</tr>
	</thead>
</tr>
<tr>
	<td>Altigram S. da Silva</td>
	<td>Professor Associado</td>
	<td>alti@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>André Luiz Carvalho</td>
	<td>Professor Adjunto</td>
	<td>andre@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>David F. de Oliveira</td>
	<td>Professor Adjunto</td>
	<td>david@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>Edleno S. de Moura</td>
	<td>Professor Associado</td>
	<td>edleno@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>João Cavalcanti</td>
	<td>Professor Associado</td>
	<td>john@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>Marco Cristo</td>
	<td>Professor Adjunto</td>
	<td>marco@icomp.ufam.edu.br</td>
</tr>
<tr>
	<td>Moises de Carvalho</td>
	<td>Professor Adjunto</td>
	<td>moises@icomp.ufam.edu.br</td>
</tr>
</body>
<!-- Fim da Página -->
</html>

5) Descreva o seguinte fluxo para edição e versionamento de arquivos, adotado pelo controle de versões do GIT. O que são o working directory, o index e o repository? Além disso, para que servem os comandos git add e git commit representados nesse fluxo?
working directoly - chamado diretório de trabalho ou diretório corrente, ou seja, o usuário estabelece nesse caso caminhos não utilizados no diretório raiz são tidos como relativos ao diretório corrente.



6) Descreva o que são estilos inline, estilos embarcados, e estilos externos. Escolha um dos três tipos de estilo e demonstre sua utilização em um código HTML/CSS.

Estilo inline é quando os estilos CSS são aplicados diretamente dentro da tag de abertura de um elemento HTML. No entanto, este tipo de uso das CSS não é recomendado e encontra-se em desuso pelos desenvolvedores WEB. 
Isso não é recomendado pelo fato de que o código CSS do estilo acima não é reaproveitado nem usado em outras páginas do site. Além disso, a manutenção deste tipo de CSS é muito complicada e difícil, gerando altos custos para o projeto. 
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Instituto de Computação</title>
</head>
<body>
<h1>Instituto de Computação</h1>
<p style="font-size: 14px; color: blue">
O Instituto de Computação (IComp), antigo Departamento
de Ciência da Computação (DCC), é um instituto
acadêmico que agrega os professores da área de
computação. Como todo instituto acadêmico o IComp atua
no ensino, pesquisa e extensão, além de desempenhar
atividades administrativas.
</p>
</body>
</html>


Sistema Embarcado- Sistema baseado em microcontroladores em que o computador é encapsulado e dedicado ao dispositivo ou sistema que ele controla; Realiza um conjunto de tarefas pré-definidas, com requisitos específicos; Além do computador dedicado, em geral possui sensores, atuadores e uma interface com o usuário. 
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Instituto de Computação</title>
<style>
p {
font-size: 14px;
color: blue;
}
</style>
</head>
<body>
<h1>Instituto de Computação</h1>
<p>
O Instituto de Computação (IComp), antigo (…)
</p>
</body>
</html>

Estilo externo - Este tipo de uso de CSS em documentos HTML é o mais indicado e recomendado. Neste tipo, os códigos CSS ficam em um documento externo ao documento HTML, separando assim as camadas de estrutura e apresentação do projeto WEB. 
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Instituto de Computação</title>
<link rel="stylesheet" href="estilo.css">
</head>
<body>
<h1>Instituto de Computação</h1>
<p>
O Instituto de Computação (IComp), antigo (…)
</p>
</body>
</html



7) Qual a diferença entre unidades relativas e unidades absolutas, usadas como medidas de tamanho na linguagem CSS. A unidade em é relativa ou absoluta? Como essa unidade é usada?

A proriedade absoluta provê grande controle sobre o local de um elemento na página. Normalmente, os elementos são posicionandos na
página na ordem em que aparecem no HTML. Especificar a posição de um elemento como absoluta ignora o fluxo normal dos elementos
Os elementos são dispostos de acordo com a distância do topo, da esquerda, da direita ou do fundo das páginas.
O CSS suporta quatro tipos de unidades absolutas:
– in: inches (polegadas)
– cm: centimetros
– mm: millimeters
– pt: points (1 ponto possui 1/72 polegadas)

A proriedade relativa posiciona um elemento em relação a sua posição original. Quando informamos o padding usando porcentagens, a porcentagem é sempre relativa ao comprimento da caixa. A altura não é levada em conta.
O CSS suporta as seguintes unidades relativas:
– em: relativo ao tamanho da fonte do elemento
– px: quantidade de pixels CSS
– %: Valor de porcentagem do valor de outra propriedade

<style>
p {
color: white;
background: grey;
height: 2em;
}
</style>
<p style="font-size: 20px">
Instituto de Computação
</p>
<p style="font-size: 14px">
Universidade Federal do Amazonas
</p>

8) De que forma as 4 declarações CSS abaixo podem ser representadas através de um único comando CSS?
padding-top: 5px;
padding-bottom: 15px;
padding-right: 0px;
padding-left: 10px;
Resposta
O padding pode ser configurado em uma única declaração chamado – Mesmo efeito:
• padding: 5px 0px 15px 10px;


9) Considere o escudo CSS abaixo (à esquerda), que é uma imagem PNG com fundo transparente de nome escudo.png. Mostre o código HTML e CSS necessário para criar a página da esquerda.
<!DOCTYPE html>
<!-- Página do Instituto de Computação -->
<html>
<head>
	<meta charset="UTF-8">
	<title>Instituto de Computação</title>
</head>
	<style type="text/css">
		img {
			border: 4px solid black;
			background: lightgray;
			margin:4px 6px;
		}
	</style>
	...
<body>
		<img src="imgs/css_pq.png" alt="CSS3">
		<img src="imgs/css_pq.png" alt="CSS3">
</body>
	<!-- Fim da Página -->
	</html>




10) Analise o código HTML/CSS e a página resultante abaixo. Que tipo de seletor CSS pode ser usado para selecionar, de uma única vez, os dois trechos com borda mostrados na página?
É possível selecionar elementos que possuem uma determinada classe, usando o atributo global class.


15) Qual é o resultado da execução do código abaixo? Porque?
(function() {
   var a = b = 5;
})();

console.log(b);
What will be printed on the console?

Resposta
The code above prints 5.

The trick of this question is that in the IIFE there are two assignments but the variable a is declared using the keyword var. What this means is that a is a local variable of the function. On the contrary, b is assigned to the global scope.

The other trick of this question is that it doesn’t use strict mode ('use strict';) inside the function. If strict mode was enabled, the code would raise the error Uncaught ReferenceError: b is not defined. Remember that strict mode requires you to explicitly reference to the global scope if this was the intended behavior. So, you should write:

(function() {
   'use strict';
   var a = window.b = 5;
})();

console.log(b);



16) Qual é o resultado da execução do código abaixo? Esse resultado sofreu a influência de hoisting?
function test() {
   console.log(a);
   console.log(foo());
   
   var a = 1;
   function foo() {
      return 2;
   }
}

test();

Resposta
The result of this code is undefined and 2.

The reason is that both variables and functions are hoisted (moved at the top of the function) but variables don’t retain any assigned value. So, at the time the variable a is printed, it exists in the function (it’s declared) but it’s still undefined. Stated in other words, the code above is equivalent to the following:

function test() {
   var a;
   function foo() {
      return 2;
   }

   console.log(a);
   console.log(foo());
   
   a = 1;
}

test();

17) Qual é o resultado da execução do código abaixo? Por que?
var fullname = 'John Doe';
var obj = {
   fullname: 'Colin Ihrig',
   prop: {
      fullname: 'Aurelio De Rosa',
      getFullname: function() {
         return this.fullname;
      }
   }
};

console.log(obj.prop.getFullname());

var test = obj.prop.getFullname;

console.log(test());

Resposta
The code prints Aurelio De Rosa and John Doe. The reason is that the context of a function, what is referred with the this keyword, in JavaScript depends on how a function is invoked, not how it’s defined.

In the first console.log() call, getFullname() is invoked as a function of the obj.prop object. So, the context refers to the latter and the function returns the fullname property of this object. On the contrary, when getFullname() is assigned to the test variable, the context refers to the global object (window). This happens because test is implicitly set as a property of the global object. For this reason, the function returns the value of a property called fullname of window, which in this case is the one the code set in the first line of the snippet.

18) Qual é a diferença entre == e ===?
== faz comparação somente de valor
=== faz comparação de valor e de tipo

19) O que são closures? Descreva o funcionamento do código abaixo.
Basicamente é uma função definida dentro de outra função. A função interna utiliza de parâmetros e variáveis da função externa.

(function() {
function foo(x) {
var baz = 3;
return function (y) {
console.log(x + y + (++baz));
}
}
var moo = foo(2); // moo agora é um closure.
moo(1); // 7
moo(1); // 8
})();

These are the parameters that matter (x e baz). They form closures involving the following function:
        return function (y) {
This function has a closure to each of the outer local variables (including moo and foo).
        console.log(x + y + (++baz));
        }
    }
There are also closures involving moo and both the above functions, however it's not used so is irrelevant to the outcome.

var moo = foo(2); // moo is now a closure.
foo() returns a function. This returned function accepts a single argument, the y you are concerned with.

So when you do this:

// returns a function that accepts `y` with `x` shared via closure
var moo = foo(2);

// execute the inner function, passing in a value for `y`.
moo(1);
foo(2) returns a function.  x is now 2.  moo is now a function that accepts a value for y, and you pass in 1. So y is now 1.

To think of it another way, you can invoke your inner function by doing:

foo(x)(y);
Or with the values you are using:

foo(2)(1);
So, in answer to your question, y gets set to 1 when you do:

moo(1);
