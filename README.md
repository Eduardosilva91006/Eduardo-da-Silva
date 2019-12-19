<!doctype html>
<html>
    <head>
        <title>Lógica de Programação com Javascript</title>
        <meta charset = 'uft-8'>
    </head>
    <body>
        <h1>Calculadora de números naturais</h1>
    <script>
//pedir nome
    var nome = prompt("Qual seu nome?");
//pedir sobrenome
    var sobrenome = prompt("Qual seu sobrenome?");
//dar boas-vindas com nome e sobrenome
    alert("Bem-vindo(a), " + nome + sobrenome);
//somar
    var n1 = prompt(nome + ", digite um número para somar");
//trocar variável para número
    n1 = parseInt(n1);
   var n2 = prompt(nome + ", digite outro número para somar");
//trocar variável para número
    n2 = parseInt(n2);
    alert (nome + ", a resposta é: " + (n1 + n2));
//subtrair
    var n3 = prompt(nome + ", digite um número para subtrair");
//trocar variável para número    
    n3 = parseInt(n3);
    var n4 = prompt(nome + ", digite outro número para subtrair");
//trocar variável para número 
    n4 = parseInt(n4);
    alert (nome + ", a resposta é: " + (n3 - n4));
//dividir
    var n5 = prompt(nome + ", digite um número para dividir");
 //trocar variável para número   
    n5 = parseInt(n5);
    var n6 = prompt(nome + ", digite outro número para dividir");
//trocar variável para número   
   n6 = parseInt(n6);
   alert (nome + ", a resposta é: " + (n5 / n6));
//multiplicar
    var n7 = prompt(nome + ", digite um número para multiplicar");
//trocar variável para número    
    n7 = parseInt(n7);
    var n8 = prompt(nome + ", digite outro número para multiplicar");
//trocar variável para número    
    n8 = parseInt(n8);
    alert (nome + ", a resposta é: " + (n7 * n8));
        </script>
    </body>
</html>
