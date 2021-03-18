# Menu principal do G1 até o G1 Bahia

## Introdução

  Este documento demonstra a navegação através da Micro Livraria com o objetivo de demonstrar o funcionamento da ferramenta Guide Automator.

## G1 screenshots

```
viewport 1365 982
go-to-page http://192.168.1.66:5000
speak 'Página principal'
screenshot "Página principal"
fill-field 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > input:nth-child(1)' '40720270';
speak 'Calculando frete'
screenshot "Cálculo do frete"
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > div:nth-child(2) > div:nth-child(2) > a:nth-child(1)'
click '.swal-button'
click 'div.column:nth-child(1) > div:nth-child(1) > div:nth-child(2) > div:nth-child(1) > button:nth-child(3)'
speak 'Compra finalizada'
screenshot "Compra finalizada"
```

## Testando