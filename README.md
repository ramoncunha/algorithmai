# algorithmia
Simple implementation of Greedy Search [Artificial Intelligence]

Feito por Ramon Cunha

-- Português

O problema:
Um agente precisa passar por diversos pontos em um mapa atrás dos objetivos.

Estados:
São quatro estados possíveis para o agente, para cima, para baixo, esquerda e direita.

Estado Inicial:
O agente sempre começa no meio do mapa.

Função Sucessor:
A função sucessora mapeia todos os estados possiveis
x + 1
x - 1
y + 1
y - 1

Função Objetivo:
Ir até o ponto de menor custo.

Custo:
O custo sempre será 1 entre as casas.

Abordagem:
Dado a posição (x, y) do agente, e posição (x+2, y-1) de um ponto qualquer. O agente deverá determinar qual o objetivo mais próximo para ir até ele. Depois de determinado o objetivo mais próximo, é necessário determinar qual dos estados deixará o agente mais próximo do objetivo escolhido.

Justificativa:
Utilizei a busca gulosa, pois, é uma forma simples e objetiva de se chegar até o objetivo.

-- English

The problem:
An agent needs to go through several points on a map behind the targets.

States:
There are 4 possible states, up, down, left and right.

Initial State:
The agent always begin in the center of map.

Successor Function:
The successor function maps all the possible states.
x + 1
x - 1
y + 1
y - 1

Objective Function:
Go to the lowest cost point.

Cost:
The cost will always be 1 between the quadrants.

Approach:
Given the position (x, y) of an agent, and position (x+2, y-1) of a random point. The agent must determine the closest goal to reach him. Once the nearest goal has been determined, it is necessary to determine which of the states will provide the closest path to the chosen goal.

Justification:
I used Greedy Search because is a simple and objective way to reach the goal.
