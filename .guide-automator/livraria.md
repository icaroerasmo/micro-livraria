# Micro Livraria UFMG

## Introdução

  Este documento demonstra a navegação através da Micro Livraria a fim de exemplificar o funcionamento do Guide Automator.

## Screenshots

```
viewport 1365 982
go-to-page http://localhost:5000
speak 'Olá! Este vídeo tem o objetivo de demonstar o funcionamento da aplicação "Micro Livraria".'
screenshot "Página principal"
```
Esta é a página principal.

```
speak 'Para calcular o frete, digite o seu CEP no campo de texto e clique no botão "Calcular Frete"'
fill-field 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > input:nth-child(1)' '40720270';
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(2) > a:nth-child(1)'
screenshot "Cálculo do frete"
```
Esta é a tela de confirmação do valor do frete.

```
speak 'Em seguida, clique no botão "Comprar"'
click '.swal-button'
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > button:nth-child(3)'
speak 'Compra finalizada'
screenshot "Compra finalizada"
```
Esta é a tela de confirmação de Compra.
