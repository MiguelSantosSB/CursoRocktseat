## Font-variant

- variações na apresentação fonte

```CSS
p{
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
  font-variant: small-caps;
}
```

## Font-stretch

- Alargamento ou encolhimento da fonte
- Aceita palavras-chave como: expanded, condensed, normal
- Aceita porcentagens de 50% a 200%

```Css
p{
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
  font-stretch: expanded;
}
```

## Letter-spacing

- Espaço entre caracteres

```Css
p{
    letter-spacing: 4px;
}
```

## word-spacing

- Espaço entre caracteres

```Css
p{
    word-spacing: 4px;
}
```

## Line-height 

- Espaços entre linhas
- Pode ser com unidades ou sem unidades de medida
- Comuns: 1.5 ou 2

```Css
p{
    line-height: 1.6;
}
```

## Text-transform

- Transformação do texto

```Css
p{
    text-transform: uppercase; /* capitalize | lowercase | none */
}
```

## Text-decoration

- Aparencia decorativa de um texto
- Line: upperline(linha a baixo da palavra) | overline(linha a cima) | line-through(linha no meio)
    * podemos aplicar mais de 1 valor 
- style: wavy | dotted | double | dashed | solid
- color: '<color>' values

```Css
p{
    text-decoration: underline; /* shorthand */
}
```

## Text-align

- Alinhamento de um texto

```Css
p{
    text-align: center; /* left | right | center | justify */
}
```

## Text-shadow

- Sombra aplicada a um texto
- Permite multiplos valores

```Css
p{
    text-shadow: 1px 1px 1px red; /* offset-x | offset-y | blur-radius | color */
}                                 /* posicionamento de x e y | embasamento | cor
```

## shorthand

- font-stryle, font-variant, font-wight, font-stretch, font-size, font-height e font-family

```Css
/*  -style, -variant, -weight, -stretch, -size, -line-height e           -family */
font: italic normal    bold     normal    3em/       1.5          Helvetica, Arial, sans-serif;
```