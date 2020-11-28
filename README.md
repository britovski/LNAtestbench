# LNATESTBENCH
## Tarefa desenvolvida para a disciplina de Circuitos de Radiofrequência, do curso de Engenharia Elétrica, UFERSA, Caraúbas, Brasil.
## Docente: Prof. Dr. Francisco de Assis Brito Filho
## Discentes: Jakson dos Santos Silva, José Ailton de Oliveira Júnior, Yago Daniel Souto
## Resumo
Este repositório apresenta a implementação e o tesbench de um circuito amplificador LNA (Low Noise Amplifier) com o uso do software ADS (Advanced Design System) para sua caracterização utilizando componentes comportamental e SMD comerciais. Resultados de simulação de ganho e resposta em frequência, linearidade (P1dB ou IIP3) e ruído (NF) serão desenvolvidos e comparados.
## Introdução
O LNA é o primeiro estágio presente no receptor após a antena captar o sinal de rádio frequência (RF). Este amplificador apresenta a característica de baixo ruído, em que, sua função é amplificar o sinal recebido de modo a evitar ao máximo que o ruído intrínseco do componente venha a alterar o conteúdo da mensagem captada. Com isso, o LNA deve ser projetado de maneira que apresente uma baixa figura de ruído (NF).
Dessa forma, para se obter uma baixa figura de ruído no LNA, é necessário escolher uma topologia simples para implementação, já que cada componente eletrônico é responsável por introduzir ruído ao sistema. Assim, o LNA pode ser baseado em topologia de um estágio, tais como: porta comum, dreno comum ou fonte comum. A topologia porta comum tem a característica de possuir facilidade em ajustar a impedância de entrada para baixos valores resistivos, de modo, a possibilitar um bom casamento de impedância. Contudo, o ajusto dessa impedância resistiva aumenta a figura de ruído do sistema. Já a topologia dreno comum fornece altos valores para a corrente de saída, no entanto, o maior ganho que pode alcançar é o valor unitário, de modo, a inviabilizar o seu uso no projeto de LNA. Para o amplificador fonte comum, a impedância de entrada pode ser ajustada para baixos valores, com característica capacitiva, além de apresentar um alto ganho de tensão na saída. Além disso, pode-se acrescentar uma degeneração indutiva e, consequentemente na entrada surgi uma componente real, que será útil para o casamento de impedância.
## Implementação da tarefa
Primeiramente, foi realizada a implementação do esquemático através do software Advanced Design System - ADS do amplificador LNA (Low Noise Amplifier) utilizando componentes ideais e SMD comerciais, como mostrado nas Figuras 1 e 2, respectivamente. 
#### Figura 1 – Esquemático do circuito amplificador LNA com componentes ideais. Fonte: Autores, 2020.
![](LNA-ideal-1.PNG)
#### Figura 2 - Esquemático do circuito amplificador LNA com componentes SMD comercial. Fonte: Autores, 2020.
![](LNA-real.PNG)
##
Os circuitos foram projetados para operar numa frequência fundamental de 2,4 GHz. O transistor FET utilizado foi importado da própria biblioteca do ADS. Na Figura 1, é apresentado o esquemático do circuito LNA com valores projetados em componentes ideais, uma vez que, será necessário realizar uma análise crítica do funcionamento do circuito através dos resultados da simulação de Parâmetros-S, ganho, resposta em frequência e ruído, com os resultados apresentado por meio do esquemático da Figura 2, com componentes SMD comerciais da fabricante Murata, inseridos na biblioteca do software ADS. A seção seguinte apresenta os resultados da simulação de ambos os circuitos implementados.
## TestBench
Ailton Jr
## Conclusões
Neste trabalho foi abordado o projeto e simulação de amplificador de baixo ruído (LNA), que no qual, foi elaborado um testbench para a caracterização do LNA utilizando componente comportamental e componentes comerciais. O testbench teve como resultado a simulação do ganho e resposta em frequência, linearidade (IIP3) e ruído (NF). Com isso, foi observado que na frequência fundamental de 2,4 GHz o ganho foi de x dB, (continuar...). Portanto, esse trabalho foi muito importante para o aprofundamento do projeto e simulação do amplificado LNA, visto que todos os objetivos foram alcançados.
## Referências
RAZAVI. RF Microelectronics. 2nd. Ed. 2011
