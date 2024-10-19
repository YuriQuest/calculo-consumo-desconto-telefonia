# Calculando Consumo e Desconto de Telefonia
## Primeiro projeto | Calculando o Consumo de Crédito em Ligações Telefônicas
### Descrição
Implemente um sistema para monitorar o uso de crédito em ligações telefônicas. Cada ligação consome uma quantidade de crédito de acordo com a sua duração e o tipo da ligação (local, nacional ou internacional). Desenvolva uma função que calcule o consumo de crédito de um cliente baseado nas suas ligações.

Cada ligação é representada por um triplo de valores: a duração da ligação (em minutos), o tipo da ligação e o valor do crédito por minuto de acordo com o tipo de ligação.

### Entrada
A entrada deverá receber:

Um número inteiro n, representando o número de ligações.
Para cada ligação, uma linha contendo os valores a seguir separados por vírgula:
Um número inteiro representando a duração da ligação em minutos.
Uma string representando o tipo da ligação (local, nacional, ou internacional).
Um número decimal representando o valor do crédito por minuto para aquele tipo de ligação.
### Saída
A função deverá retornar o consumo total de crédito em uma única linha. O resultado deve ser um número decimal com duas casas decimais.

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada	1| Entrada	2| Entrada	3| Entrada	4|Saída
--|--|--|--|--
3|10,local,0.10|5,nacional,0.20|2,internacional,0.50	|3.00
2|20,local,0.05|3,internacional,0.35|	|2.05
1|5,nacional,0.10|	||0.50
## Segundo projeto | Cálculo de Desconto Progressivo em Combo
### Descrição
Implemente um programa que calcule o valor total de um combo de serviços (telefonia móvel, banda larga e TV por assinatura) aplicando um desconto progressivo baseado na quantidade de serviços contratados. Cada serviço adicional contratado além do primeiro aumenta o desconto. A implementação deve utilizar Programação Orientada a Objetos (POO) para representar os serviços e os descontos.

Para resolver este desafio, considere:

- Limite de Serviços: O combo pode ter no máximo três serviços.
- Valores de Serviço: Cada serviço tem um valor individual.
- Serviço Não Contratado: Se o valor de um serviço for 0, significa que o serviço não foi contratado.
- Desconto Progressivo: O desconto é aplicado de forma progressiva conforme fornecido na entrada:
  - 1 serviço contratado: desconto1% de desconto
  - 2 serviços contratados: desconto2% de desconto
  - 3 serviços contratados: desconto3% de desconto
- Serviço Especial: Se o usuário contratar todos os três serviços, um desconto adicional fixo de R$ 20,00 é aplicado ao valor final após o desconto progressivo.
### Entrada
A entrada deve ser fornecida em duas linhas:

A primeira linha contém os valores dos serviços contratados separados por vírgulas (telefonia móvel, banda larga, TV por assinatura). Um valor 0 indica que o serviço não foi contratado.
A segunda linha contém os percentuais de desconto para 1, 2 e 3 serviços contratados respectivamente, também separados por vírgulas.
Saída
Deverá retornar o valor total com o desconto aplicado.

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada	1 |Entrada	2 |Saída
--|--|--
50,70,0|5,10,15	|108.00
69,89,119|7,10,20|	201.60
0,59,99|3,5,10|	150.10