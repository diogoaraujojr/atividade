# Atividade margin, padding e border


## Margin

- As propriedades de margem CSS são usadas para criar espaço ao redor dos elementos, fora de quaisquer bordas definidas.

- As margens definem a distância entre a borda de um elemento e os elementos circundantes.

- Com CSS, você tem controle total sobre as margens. O CSS possui propriedades para definir a margem de cada lado individual de um elemento (superior, direita, inferior e esquerda), além de uma propriedade abreviada para definir todas as margens em uma única declaração.

### Como usar
O CSS possui propriedades para especificar a margem de cada lado de um elemento:

-   `[margin-top]`- define a margem superior de um elemento
-   `[margin-right]`- define a margem direita de um elemento
-   `[margin-bottom]`- define a margem inferior de um elemento
-   `[margin-left]`- define a margem esquerda de um elemento

Exemplo:

```
#elemento {
    margin-top: 15px;
    margin-right: 10px;
    margin-bottom: 25px;
    margin-left: 35px;
}
```

## Padding

- As propriedades de preenchimento (padding) do CSS são usadas para gerar espaço ao redor do conteúdo de um elemento, dentro de quaisquer bordas definidas.

- Com CSS, você tem controle total sobre o preenchimento (padding). Existem propriedades para definir o preenchimento de cada lado de um elemento (superior, direito, inferior e esquerdo), e uma propriedade abreviada para definir todas as propriedades de preenchimento em uma única declaração.

### Como usar

O CSS possui propriedades para especificar o preenchimento (padding) de cada lado de um elemento:

-   `[padding-top]`- define o espaçamento superior de um elemento
-   `[padding-right]`- define o espaçamento correto de um elemento
-   `[padding-bottom]`- define o espaçamento inferior de um elemento
-   `[padding-left]`- define o espaçamento à esquerda de um elemento

Exemplo:
````
#elemento {  
padding-top:  50px;  
padding-right:  30px;  
padding-bottom:  50px;  
padding-left:  80px;  
}
````

## Border

- As propriedades de borda em CSS permitem especificar o estilo, a largura e a cor da borda de um elemento.

### Como usar

Essa propriedade especifica o tipo de borda a ser exibida. `[border-style]`

Os seguintes valores são permitidos:

-   `dotted`- Define uma borda pontilhada
-   `dashed`- Define uma borda tracejada
-   `solid`- Define uma borda sólida
-   `double`- Define uma borda dupla
-   `groove`- Define uma borda com ranhuras em 3D. O efeito depende do valor da cor da borda.
-   `ridge`- Define uma borda texturizada em 3D. O efeito depende do valor da cor da borda.
-   `inset`- Define uma borda interna 3D. O efeito depende do valor da cor da borda.
-   `outset`- Define uma borda inicial 3D. O efeito depende do valor da cor da borda.
-   `none`- Não define nenhuma fronteira
-   `hidden`- Define uma borda oculta

Exemplo:
p.dotted {border-style:  dotted;}  
p.dashed {border-style:  dashed;}  
p.solid {border-style:  solid;}  
p.double {border-style:  double;}  
p.groove {border-style:  groove;}  
p.ridge {border-style:  ridge;}  
p.inset {border-style:  inset;}  
p.outset {border-style:  outset;}  
p.none {border-style:  none;}  
p.hidden {border-style:  hidden;}  
p.mix {border-style:  dotted dashed solid double;}
