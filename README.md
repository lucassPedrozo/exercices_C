attendanceList:
Contagem de Registros Únicos
Em um sistema de cadastro de registros, você precisa implementar um programa que leia N registros numéricos e conte quantos registros únicos (sem repetições) foram informados. A entrada pode conter números repetidos, mas o objetivo é contar apenas os números distintos.

Requisitos:
O programa deve ler um valor inteiro N que indica a quantidade de registros a serem informados.
O programa deve ler N números inteiros. Se um número informado for menor ou igual a 0, o programa deve ignorá-lo e pedir o próximo número.
O programa deve contar apenas os registros únicos, ou seja, se um número for repetido, ele deve ser desconsiderado na contagem final.
Ao final, o programa deve imprimir a quantidade de registros únicos informados.


---------------------------------------------------------------------------------------------------------------------
binaryAndOctalConvert:
Conversão de Números para Binário e Octal
Você precisa desenvolver um programa que leia um número decimal e forneça sua representação binária e octal. O programa deve continuar processando números até que o usuário forneça um valor negativo para encerrar.

Requisitos:
O programa deve ler um número decimal e convertê-lo para binário e octal.
O programa deve continuar pedindo números até que um número negativo seja informado, momento em que o programa deve terminar.
A conversão para binário deve exibir o número binário sem espaços adicionais, começando com o bit mais significativo.
A conversão para octal deve exibir o número octal, sem espaços à frente e de forma compacta.
Se o número for 0, o programa deve imprimir "0 0" e encerrar.

---------------------------------------------------------------------------------------------------------------------
containers:
Cálculo de Capacidade de Armazenamento de Contêineres em um Navio
Você está desenvolvendo um sistema para calcular a quantidade de contêineres que um navio pode transportar, levando em consideração as dimensões dos contêineres e as dimensões do navio. O programa deve calcular quantos contêineres cabem no navio, levando em conta a largura, comprimento e altura de ambos.

Requisitos:
O programa deve ler as dimensões de um contêiner (largura, comprimento e altura).
O programa deve ler as dimensões do navio (largura, comprimento e altura).
O programa deve verificar se as dimensões dos contêineres e do navio são válidas (nenhuma dimensão pode ser negativa).
O programa deve calcular:
  Quantos contêineres cabem na largura do navio (considerando a largura do contêiner).
  Quantos contêineres cabem no comprimento do navio (considerando o comprimento do contêiner).
  Quantos contêineres cabem na altura do navio (considerando a altura do contêiner).
O número total de contêineres que o navio pode transportar, multiplicando os valores obtidos nas dimensões horizontal, vertical e de altura.
O programa deve imprimir a quantidade total de contêineres que o navio pode transportar.

---------------------------------------------------------------------------------------------------------------------
divers:
Identificação de Mergulhos Faltantes
Você está desenvolvendo um sistema para registrar a quantidade de mergulhos realizados por um grupo de mergulhadores. O objetivo do programa é identificar quais mergulhos ainda não foram realizados, a partir de um total de mergulhos possíveis.

Requisitos:
O programa deve ler o número total de mergulhos possíveis (totalMerg).
O programa deve ler o número total de mergulhos que foram realizados (totalVolta).
O programa deve ler os números de cada mergulho realizado e marcar esses mergulhos.
O programa deve identificar quais mergulhos ainda não foram realizados, exibindo o número desses mergulhos.
Caso o número total de mergulhos realizados seja igual ao número total de mergulhos possíveis, o programa deve exibir um asterisco (*) e encerrar.
O programa deve verificar se os valores fornecidos são válidos (números positivos para o total de mergulhos e mergulhos realizados). Caso contrário, deve exibir "ERRO" e encerrar.

---------------------------------------------------------------------------------------------------------------------
shoesBox:
Contagem de Pares de Sapatos
Você está desenvolvendo um programa para contar quantos pares de sapatos foram formados a partir de um conjunto de sapatos. Cada sapato é identificado pelo número do tamanho e pela letra que indica se ele foi adicionado ou retirado.

Requisitos:
O programa deve ler o número total de operações (n).
Para cada operação, o programa deve ler o tamanho do sapato (tam) e a letra (pe), que pode ser:
'D' (Dominó): Indica que o sapato foi adicionado.
'E' (Empréstimo): Indica que o sapato foi retirado.
O programa deve formar pares de sapatos do mesmo tamanho: quando um sapato do tipo 'D' (dominó) for adicionado e um sapato do tipo 'E' (empréstimo) do mesmo tamanho for retirado, um par de sapatos é formado.
O programa deve contar quantos pares de sapatos foram formados e imprimir o total.

---------------------------------------------------------------------------------------------------------------------
waterBill:
Cálculo do Custo do Consumo de Água
Você está desenvolvendo um sistema para calcular o custo do consumo de água com base no volume consumido em metros cúbicos. O custo do consumo de água varia conforme o volume utilizado, com diferentes tarifas para diferentes faixas de consumo.

Requisitos:
O programa deve ler o volume de água consumido em metros cúbicos (metroCubico).
O custo do consumo de água é calculado de acordo com as seguintes faixas:
Para os primeiros 10 metros cúbicos, o custo é 9 por metro cúbico.
Para o consumo entre 11 e 30 metros cúbicos, o custo aumenta 1 por metro cúbico.
Para o consumo entre 31 e 100 metros cúbicos, o custo aumenta 2 por metro cúbico.
Para o consumo acima de 100 metros cúbicos, o custo aumenta 5 por metro cúbico.
O programa deve calcular o valor total do consumo com base nas regras acima e imprimir o valor total formatado com duas casas decimais.
