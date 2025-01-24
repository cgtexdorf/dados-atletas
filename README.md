# dados-atletas
Repositório criado para publicação do Projeto de certificação 2 - Dados dos atletas | Curso Devstart

Este projeto é uma aplicação que recebe informações de um atleta, como nome, idade, peso, altura e notas dos jurados. A aplicação calcula a categoria, o IMC e a média válida do atleta, e exibe essas informações de maneira organizada.

## Funcionalidade

1. **Calcular a categoria do atleta** com base na idade.
2. **Calcular o IMC** usando a fórmula `IMC = peso / (altura * altura)`.
3. **Calcular a média válida das notas**, desconsiderando a maior e a menor nota.

## Exemplo de uso

```javascript
const atleta = new Atleta("Cesar Abascal", 30, 80, 1.70, [10, 9.34, 8.42, 10, 7.88]);
console.log(atleta.obtemNomeAtleta());
console.log(atleta.obtemIdadeAtleta());
console.log(atleta.obtemPesoAtleta());
console.log(atleta.obtemIMC());
console.log(atleta.obtemMediaValida());
**` ``` `** 

Como executar  
Clone o repositório:  
git clone https://github.com/seu_usuario/dados-atletas.git  
Abra o arquivo dados-atletas.js e execute-o em um ambiente JavaScript.
