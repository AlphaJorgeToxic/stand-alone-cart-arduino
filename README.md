# Carrinho autônomo capaz de desviar de obstáculos com Arduino

Esse projeto foi um desenvolvimento de um robô, no qual tem como base o Arduino, que consiste em simular um veículo autônomo que identifica obstáculos através de um sensor ultrassônico que mede a distância e define a melhor rota e um infravermelho que identifica objetos, degraus e depressões, possibilitando-o desviar dos mesmos. A programação do robô foi desenvolvida utilizando a linguagem C no software de desenvolvimento do Arduino.

## Participantes
1- Davi Marcelino <br />
2- Gabriel Aragão Alonso <br />
3- Maria Elizabeth <br />
4- Maycon Robert Brolacci <br />
5- Samuel Ferracini <br />

## Disciplina
Eletrônica, Engenharia da Computação, 4º Semestre.

## Componentes
•	Arduino
•	Ponte H Direção
•	Servo motor
•	Sensor ultrassônico
•	Sensor infravermelho
•	Motores
•	Rodas
•	Base acrílica
•	Resistores


## Resultados e Discussões:
Foi dado início do projeto com a programação, definindo como iremos programar cada componente a parte fazendo diversos testes de funcionamento e precisão dos seguintes componentes: infravermelho, sensor ultrassônico e motor. Após os testes, observamos como deveríamos programar cada componente e também analisamos suas precisões. <br /> 
Passamos então para montagem do robô, no qual tivemos dificuldade com o tamanho da base e tivemos que desistir da ideia de utilizar os dois protoboards, consequentemente não foi possível utilizar o BarGraph, pois não tinha a quantidade necessária de portas lógicas. Seguimos com a montagem dos componentes básicos nos quais são: protoboard, Arduino, duas baterias, motores, Servomotor e os sensores. <br />
Após a finalização da montagem começamos efetivamente programar o robô com suas funções essenciais para realizar seus objetivos, nos quais consistem em evitar quedas e desviar de objetos. Tivemos dificuldade com a programação do servo motor, pois não havíamos feito teste antes separadamente, visto que foi uma peça que demoramos para adquirir. Tivemos dificuldade na questão dos cálculos de graus e a lógica de virar o sensor ultrassônico, mas apesar disso conseguimos resolver o problema após algumas pesquisas. <br />
Dessa forma então finalizamos o projeto com sucesso e com todos os objetivos propostos, nos quais se consistem em evitar quedas com sensor infravermelho, analisar se há a presença de chão ou não, e colisões com sensor ultrassônico acoplado ao servo motor para analisar se há um objeto na frente e visualizar qual direção não se encontra obstáculos.

## Abaixo algumas imagens do projeto no TinkerCad

![image](https://user-images.githubusercontent.com/25436067/112561976-14a6ba00-8db5-11eb-9cec-806167113fe9.png)

![image](https://user-images.githubusercontent.com/25436067/112561998-1e302200-8db5-11eb-8268-9fe931bfdc8c.png)

![image](https://user-images.githubusercontent.com/25436067/112562027-2be5a780-8db5-11eb-9049-41b76e86ecbd.png)

