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
- integrar de forma externa o arquivo ***

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