# primeiros-passos-com-javascript
Programa que calcula o valor de uma viagem

/* Faça um programa para calcular o valor de viagem.

Você terá 3 variáveis. Sendo elas:
1- Preço do combustível;
2- Gasto médio de combustível do carro por km;
3- Distância em km da viagem;

*/

//Entradas do programa//
const precoCombustivel = 5.79;
const kmPorLitros = 10;
const distanciaEmKm = 100;

//Cálculos do programa//
const litrosConsumidos = distanciaEmKm / kmPorLitros;
const valorGasto = litrosConsumidos * precoCombustivel;
console.log(valorGasto);
