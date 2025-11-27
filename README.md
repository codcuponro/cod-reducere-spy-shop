# Cod Reducere Spy Shop

O colecție de coduri de reducere Spy Shop. Le folosim pentru testarea cuvintelor cheie [cod reducere Spy Shop](https://cuponescu.ro/magazin/spy-shop), [voucher Spy Shop](https://cuponescu.ro/magazin/spy-shop), [cupon Spy Shop](https://cuponescu.ro/magazin/spy-shop), și [cod promotional Spy Shop](https://cuponescu.ro/magazin/spy-shop) de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-spy-shop` prin NPM:

```bash
npm install cod-reducere-spy-shop
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-spy-shop')

console.log(codes)

// [
//   {
//     site: 'https://www.spy-shop.ro',
//     cod_reducere: 'SPY10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-spy-shop a fost creat de echipa de la [Cuponescu](https://cuponescu.ro/) pentru a ajuta cu testarea.
