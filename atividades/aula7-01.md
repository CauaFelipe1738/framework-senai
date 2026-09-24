# CSS Vanilla, Flexbox
A atividade propõe a criação de um projeto web básico com HTML e CSS, sem frameworks.
O objetivo dessa atividade é relembrar os conceitos de flexbox, estilização com CSS externo e Padding, Border e Margin.

## Especificação
Como visto na documentação da aula 7, a atividade requer 20 elementos com atribuição de Margin, Border e Padding, e 20 propriedades de Flexbox

## Solução proposta

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div id="c1">
        <p class="one">teste</p>
        <p class="two">teste</p>
        <p class="three">teste</p>
        <p class="four">teste</p>
    </div>

    <div id="c2">
        <p class="one">teste</p>
        <p class="two">teste</p>
        <p class="three">teste</p>
        <p class="four">teste</p>
    </div>

    <div id="c3">
        <p class="one">teste</p>
        <p class="two">teste</p>
        <p class="three">teste</p>
        <p class="four">teste</p>
    </div>

    <div id="c4">
        <p class="one">teste</p>
        <p class="two">teste</p>
        <p class="three">teste</p>
        <p class="four">teste</p>
    </div>

    <div id="c5">
        <p class="one">teste</p>
        <p class="two">teste</p>
        <p class="three">teste</p>
        <p class="four">teste</p>
    </div>
</body>
</html>
```
### style.css
```css
#c1{
    display: flex;
    background-color: #ff0000;
    margin: 1rem;
    flex-direction: column;
}

#c2{
    display: flex;
    background-color: #52d65b;
    margin: 2rem;
    flex-direction: row-reverse;
}

#c3{
    display: flex;
    background-color: #222787;
    margin: 1rem 2rem;
    flex-direction: column-reverse;
    flex-wrap: wrap;
}

#c4{
    display: flex;
    background-color: #b91358;
    margin: 1rem;
    flex-direction: row;
}

#c5{
    display: flex;
    background-color: #43e3c8;
    margin: 4rem;
    flex-direction: row;
}

p{
    background-color: #fff;
    width: fit-content;
}

.one{
    padding: 1rem;
    color: #9f1e1e;
}

.two{
    padding: 1rem;
    color: #452d99;
}

.three{
    padding: 1rem;
    color: #37a87b;
}

.four{
    padding: 1rem;
    color: #a737bd;
}
```
