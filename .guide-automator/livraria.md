# Micro Livraria UFMG

## Introdução

  Este documento demonstra a navegação através da Micro Livraria a fim de exemplificar o funcionamento do Guide Automator.

## Screenshots

```
viewport 1365 982
go-to-page http://192.168.1.66:5000
speak 'Página principal'
screenshot "Página principal"
```
Esta é a página principal.

```
fill-field 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > input:nth-child(1)' '40720270';
speak 'Calculando frete'
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(2) > a:nth-child(1)'
screenshot "Cálculo do frete"
```
Esta é a tela de confirmação do valor do frete.

```
click '.swal-button'
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > button:nth-child(3)'
speak 'Compra finalizada'
screenshot "Compra finalizada"
```
Esta é a tela de confirmação da Compra.