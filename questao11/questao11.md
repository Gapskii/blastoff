# QUESTÃO 11. Na função JavaScript a seguir, responda quais serão os resultados respectivos:

~~~javascript
function multiplicacao (num1,num2) {
 let resultado = num1 * num2;
 return resultado;
}
multiplica(4, 7);
multiplica(5, 6);
multiplica(3, 3);
~~~

Resposta: Para todas elas, devido ao erro de referência ao se chamar a função 'multiplicacao', não há resultado per se, mas é devolvido o seguinte erro: "Uncaught ReferenceError: multiplica is not defined".