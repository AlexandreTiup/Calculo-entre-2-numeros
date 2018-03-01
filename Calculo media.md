# Calculo-entre-2-numeros
Calcular o estoque médio de uma peça
inicio
	inteiro quantmin
	inteiro quantmax
	inteiro soma
	quantmin <- 0
	quantmax <- 0
	soma <- 0
	ler quantmin
  ler quantmax
	soma <- 0
	soma <- ( quantmin + quantmax ) / 2
	escrever "A quantidade média no estoque é:" , soma
fim
