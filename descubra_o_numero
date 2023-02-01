var numeroSecreto = parseInt(Math.random() * (1001 - 1) + 1)
var qtdTentativas = 0

while (chute != numeroSecreto) {
  var chute = prompt ('Digite um número de 1 à 1000')
  
  if (chute == numeroSecreto) {
    alert ('Acertou! Sua quantidade de tentativas foram ' + qtdTentativas)
  } else if (chute > numeroSecreto) {
    alert ('Errou, o ' + chute + ' é maior que o número secreto')
  } else if (chute < numeroSecreto) {
    alert ('Errou, o ' + chute + ' é menor que o número secreto')
  }
  
  qtdTentativas = qtdTentativas + 1
}