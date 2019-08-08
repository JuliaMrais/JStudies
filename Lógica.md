# Lógica booleana

No século 19, George Boole desenvolveu um sistema algébrico de operações binárias entre  `0` e `1`, contendo os seguintes operadores :
* `And` ( *  ,  Λ)
* `Or` ( + , ⋁ )
* `NOT` ( ¬ ) 

Essa álgebra é nomeada de álgebra booleana e é usada nos computadores atuais para as operações que exigem de alguma condição.

As operações são feitas comparando valores de `0` e `1`

## Exemplos:

### `AND`

A operação `AND` compara se os dois são valores são verdadeiros(`1`), ou seja, as duas situações tem que ser verdadeiras.

` 1 and 1 --> 1`

` 1 and 0 --> 0`

` 0 and 1 --> 0`

` 0 and 0 --> 0`

### `OR`

A operação `OR` compara se em pelo menos um dos valores há uma entrada verdadeira, ou seja, se pelo menos uma das entradas recebe o valor `1`.

` 1 or 1 --> 1`

` 1 or 0 --> 1`

` 0 or 1 --> 1`

` 0 or 0 --> 0`

### `NOT`
O operador `NOT` inverte o sinal recebido na entrada. Então se recebermos `1` o operador `NOT` converte para `0`.

` NOT 1 --> 0`

` NOT 0 --> 1`

<br>
<br>

## Tabela verdade

A tabela verdade é uma representação de todas as operações realizadas com duas hipóteses, ou seja, duas entradas.

Então sendo *P* e *Q* duas entradas, aqui temos tabelas para cada operação, com todas as combinações de possibilidades.

### Tabela do `AND`

*P*          |       *Q*     | *P Λ Q*     
------------ | ------------- | -----------------  
`1`          | `1`           | `1`           
`1`          | `0`           | `0`           
`0`          | `1`           | `0`           
`0`          | `0`           | `0`                    

### Tabela do `OR`

*P*          |       *Q*       |       *P ⋁ Q*      
------------ | ------------- | -------------  
`1`          | `1`           | `1`           
`1`          | `0`           | `1`           
`0`          | `1`           | `1`           
`0`          | `0`           | `0`                       

### Tabela do `NOT`

*P*          |       *Q*     |       *¬P*    |      *¬Q*     |
------------ | ------------- | ------------- | ------------- | 
`1`          | `1`           | `0`           | `0`
`1`          | `0`           | `0`           | `1`
`0`          | `1`           | `1`           | `0`
`0`          | `0`           | `1`           | `1`            

