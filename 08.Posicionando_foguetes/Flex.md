# Flexbox

- Permite posicionar os elementos dentro da caixa.
- Controle em uma dimensão (horizontal ou vertical)
- Alinhamento, direcionamento, ordernar e tamanhos

```Css
div.parent{
    diplay: flex;
}
```

## Flex-direction

- Qual a direção do flex: horizontal ou vertical
- row | column

## Alinhamento

- justify-content
- align-items


```HTML
<div class="container">
  <div class="box blue"></div>
  <div class="box red"></div>
  <div class="box green"></div>
</div>  
```

```Css
.container{
 height: 100vh;
 align-items: center;
 display: flex;
}
.box{
  width: 50px;
  height: 50px;
  margin-left: 8px;
}
.blue{
  background-color: blue;
}
.red{
  background-color: red;
}
.green{
  background-color: green;
}

```
