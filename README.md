
# Cifra de cesar

A cifra de César é um método de criptografia simples que consiste em substituir cada letra de uma mensagem por outra letra, que está um número fixo de posições mais adiante no alfabeto. Esse número é conhecido como a chave da cifra. Por exemplo, se a chave for 3, então a letra "A" seria substituída pela letra "D", a letra "B" seria substituída pela letra "E" e assim por diante. A decodificação da mensagem criptografada é feita usando a chave inversa.

## Sobre o codigo

### Funcionamento da cifra em JavaScript

### Resumo

- [Dividir cada letra do texto](#dividir)
- [Transformar cada letra em numero](#transformar)
- [Filtragem de dados](#filtagrem)
- [Rotacao](#rotacao)
- [Texto cifrado](#textoCifrado)

>>#### 1. <a id="dividir"></a>Dividir cada letra do texto
>>
>>```js
>>const textoSplit = texto.split("");
>>```