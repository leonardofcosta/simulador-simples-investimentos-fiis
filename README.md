# Ferramenta Simples de Controle de Investimentos com Excel

Baseado em Fundos Imobiliários (FIIs).

## Perguntas de negócio:

* Quanto investir por mês?
* Por quantos anos ?
* Qual a taxa de rendimento mensal ?
* Quanto terei de patrimônio acumulado ?
* Dividendos mensais ?

Para responder as perguntas acima, no quadro **Investimentos Mensal**, foi adicionado valores fixos nas 3 primeiras perguntas e nas duas últimas os valores foram calculados. No Patrimônio acumulado foi utilizado a função financeira VF (Valor Futuro) que calcula valor de um investimento com base em uma taxa de juros constante.

VF(taxa,nper,pgto):
* taxa: A taxa de juros por período;
* nper: O número de períodos;
* pagto: O pagamento feito a cada período.

No quadro **Cenários** foi adicionado para projetar a evolução do patrimônio acumulado ao longo do tempo e seus respectivos dividendos.

Em **Configurações** foi adicionado as variáveis: Salário, Rendimento Carteira e Sugestão de Investimento (Onde é sugerido o quanto investir com base no salário da pessoa, nesse simulador foi estipulado 30% do salário.)

No campo **perfil** é possível selecionar o tipo de investidor: Conservador, Moderado ou Agressivo e na tabela abaixo visualizar o percentual sugerido para os tipos de FII baseado no valor a ser investido por mês.

### Fontes: 
* Ajuda do MS-Excel;
* Videoaulas do curso: Criando uma Ferramenta de Controle de Investimentos com Excel.

