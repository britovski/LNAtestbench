# LNATESTBENCH
## Tarefa desenvolvida para a disciplina de Circuitos de Radiofrequência, do curso de Engenharia Elétrica, UFERSA, Caraúbas, Brasil.
## Docente: Prof. Dr. Francisco de Assis Brito Filho
## Discentes: Jakson dos Santos Silva, José Ailton de Oliveira Júnior, Yago Daniel Souto
## Resumo
Este repositório apresenta a implementação e o tesbench de um circuito amplificador LNA (Low Noise Amplifier) com o uso do software ADS (Advanced Design System) para sua caracterização utilizando componentes comportamental e SMD comerciais. Resultados de simulação de ganho e resposta em frequência, linearidade (P1dB ou IIP3) e ruído (NF) serão desenvolvidos e comparados.
## Introdução
## Implementação da tarefa
Primeiramente, foi realizada a implementação do esquemático através do software Advanced Design System - ADS do amplificador LNA (Low Noise Amplifier) utilizando componentes ideais e SMD comerciais, como mostrado nas Figuras 1 e 2, respectivamente. 
#### Figura 1 – Esquemático do circuito amplificador LNA com componentes ideais. Fonte: Autores, 2020.
![](LNA-ideal-1.PNG)
#### Figura 2 - Esquemático do circuito amplificador LNA com componentes SMD comercial. Fonte: Autores, 2020.
![](LNA-real.PNG)
##
Os circuitos foram projetados para operar numa frequência fundamental de 2,4 GHz. O transistor FET utilizado foi importado da própria biblioteca do ADS. Na Figura 1, é apresentado o esquemático do circuito LNA com valores projetados em componentes ideais, uma vez que, será necessário realizar uma análise crítica do funcionamento do circuito através dos resultados da simulação de Parâmetros-S, ganho, resposta em frequência e ruído, com os resultados apresentado por meio do esquemático da Figura 2, com componentes SMD comerciais da fabricante Murata, inseridos na biblioteca do software ADS. A seção seguinte apresenta os resultados da simulação de ambos os circuitos implementados.
## TestBench
## Conclusões
## Referências
RAZAVI. RF Microelectronics. 2nd. Ed. 2011
