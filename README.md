# Paulo_trab_1
Esse programa, codigo criado em Matlab, tem como intuito calcular a nota mínima na 
Verificação Final para que um aluno consiga passar de ano sem fazer a prova de recuperação.
O programa irá pedir inicialmente o número de VE's feitas pelo aluno para calcular a média das VE's(MVE).
O programa, então, entra num loop onde, considerando que todas as VE's tem mesmo peso, pedira n vezes a 
nota da VE de forma que cada valor será adicionado ao valor salvo na variável MVE.
Após adquirir todas as notas de VE's ele fará a média dividindo MVE por n e salvando em MVE novamente.
Por fim ele irá pedir a nota de VC e calculará através da formula VF=10-((VC+MVE)/2) e imprimirá o valor de VF na tela.