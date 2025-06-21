# Fundamentos do javaScript clássico 

## INTEGRAÇÕES

### integrar Javascript de forma interna

~~~ html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript</title>
</head>
<body>


    <script src="./src/script.js"></script>
</body>
</html>
~~~ 

### integrar javascript de forma externa

- Criar diretório ***src*** na raiz do projeto
- Criar arquivo ***script.js*** na raiz do diretório ***src***
- integrar de forma externa o arquivo ***script.js*** no arquivo ***index.html***

~~~ html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript</title>
</head>
<body>

    <script defer>
        console.log("hello world");
    </script>
</body>
</html>
~~~

## COMENTÁRIOS 

### comentário de linha 

~~~ javascript 
./src/script.js
//comentário de linnha 

~~~

### comentário de bloco simples 

~~~ javascript
./src/script.js 

/* comentário de bloco simples */

~~~

### comentário de bloco com marcadores 

~~~ javascript 
./src/script.js
/**
 * comentário de bloco com marcador
 */


## VARIAVEIS

### declaração

~~~ javascript 
./src/script.js

### Atribuição de valor 

~~~ javascript 
./src/script.js

var number; 

Number = 5;

### Declaração e atribuição de valor 

~~~ javascript 
./src/script.js

var number = 5;

### reatribuição de valor

~~~ javascript 
./src/script.js

var number = 5;

number = 10; 

### Nomenclaturas

-caracteres permitidos para iniciar a nomenclatura de um indicador

~~~ javascript 
./src/script.js

//letras 
var number:
var Number:

//"Number" é diferente de "number"

//sublinhado

var _number;

//cifrão
var $number:

~~~

-nomenclaturas compostas 

~~~ javascript 
./src/script.js

~~~
## TIPOS DE DADOS 

### Primitivos 

//camel case
var myname;

//pascal case
var Myname;

//snake case
var my_name;