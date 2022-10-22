# CSS Units - Um guia das unidades de CSS

Cascading Style Sheets oferece diversas unidades de medidas para diferentes propósitos, cobri as principais porém existem diversas outras.

## Px

Px são medidas abosulates. Por exemplo, se definirmos 100px para a largura de um elemento, em todas as telas esse elemento vai ser sempre igual.

# %

A porcentagem é sempre baseada no tamanho do elemento pai, caso não tenha uma tag em torno dela, o tamanho vai ser relativo ao body e o comportamento vai ser igual aos das medidas de ViewPort.
Da pra usar porcentagem como font-size também, elas são exatamente iguais a EM, font-size: 200%; é igual a font-size: 2em;

## Vw & Vh

Vw e Vh são medidas relativas ao tamanho da tela, vw à largura e vh à altura.

## Rem

Rem (ROOT em) é uma medida relativa ao tamanho da fonte na raiz do HTML, por padrão esse tamanho são 16px, então 1rem = 16px. Uma prática comum é definir o font-size para 62.5% no elemento raiz <html>, assim fica mais fácil de calcular o tamanho quando se usar REM. Assim, 2.4rem seria igual a 24px.

## Em

Em é bem parecido com o rem, porém com uma diferença crucial. Em é relativo ao tamanho da fonte do elemento pai, então se uma div contém uma font-size: 30px; agora 1em significa 30px.
