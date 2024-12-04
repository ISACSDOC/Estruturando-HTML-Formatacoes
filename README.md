# Estruturando HTML + Formatações
## Formatando textos
```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estruturando HTML + Formatações</title>
</head>
<body>
    <font color="red" face="Arial, Tahoma"><i>Programe</i> o seu <b>futuro</b> <mark>global</mark> <u>agora</u>!</font><br>
    <strong>Usar o strong semanticamente deixa mais óbvio</strong>

</body>
</html>
```
## Div e Span
```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estruturando HTML + Formatações</title>
</head>
<body>
    <div id="menu-lateral">
        <div id="links">
            <ul>
                <li><a href="#">Link1</a></li>
                <li><a href="#">Link2</a></li>
                <li><a href="#">Link3</a></li>
            </ul>
        </div>
    </div>
</body>
</html>
```
```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estruturando HTML + Formatações</title>
    <style>
        span{
            color: powderblue;
        }
    </style>
</head>
<body>
    <p>Dio<span>.</span>me</p>
</html>
```  
## Fieldset
```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estruturando HTML + Formatações</title>
    <style>
        label {
            width: 100px;
            text-align: right;
            display: inline-block;
            padding: 5px;
        }
        fieldset {
            border-radius: 10px;
            margin: 15px 0;
            border-color: powderblue;
        }
    </style>
</head>
<body>
    <fieldset>
        <legend>Dados Pessoais</legend>
        <label for="">Nome:</label><input type="text"><br>
        <label for="">Idade:</label><input type="text"><br>
    </fieldset>
    <button type="submit">Enviar</button>
</body>
</html>
```
