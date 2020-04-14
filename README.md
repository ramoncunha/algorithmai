# algorithm ai
Simple implementation of Greedy Search [Artificial Intelligence]

<p>Feito por Ramon Cunha<br>
Enjoy it!</p>

-- Português

**O problema:**
<p>Um agente precisa passar por diversos pontos em um mapa atrás dos objetivos.</p>

**Estados:**
<p>São quatro estados possíveis para o agente, para cima, para baixo, esquerda e direita.</p>

**Estado Inicial:**
<p>O agente sempre começa no meio do mapa.</p>

**Função Sucessor:**
<p>A função sucessora mapeia todos os estados possiveis
<ul>
  <li>x + 1</li>
  <li>x - 1</li>
  <li>y + 1</li>
  <li>y - 1</li>
</ul>
</p>

**Função Objetivo:**
<p>Ir até o ponto de menor custo.</p>

**Custo:**
<p>O custo sempre será 1 entre as casas.</p>

**Abordagem:**
<p>Dado a posição (x, y) do agente, e posição (x+2, y-1) de um ponto qualquer. O agente deverá determinar qual o objetivo mais próximo para ir até ele. Depois de determinado o objetivo mais próximo, é necessário determinar qual dos estados deixará o agente mais próximo do objetivo escolhido.</p>

**Justificativa:**
<p>Utilizei a busca gulosa, pois, é uma forma simples e objetiva de se chegar até o objetivo.</p>

-- English

**The problem:**
<p>An agent needs to go through several points on a map behind the targets.</p>

**States:**
<p>There are 4 possible states, up, down, left and right.</p>

**Initial State:**
<p>The agent always begin in the center of map.</p>

**Successor Function:**
<p>The successor function maps all the possible states.
<ul>
  <li>x + 1</li>
  <li>x - 1</li>
  <li>y + 1</li>
  <li>y - 1</li>
</ul>
</p>

**Objective Function:**
<p>Go to the lowest cost point.</p>

**Cost:**
<p>The cost will always be 1 between the quadrants.</p>

**Approach:**
<p>Given the position (x, y) of an agent, and position (x+2, y-1) of a random point. The agent must determine the closest goal to reach him. Once the nearest goal has been determined, it is necessary to determine which of the states will provide the closest path to the chosen goal.</p>

**Justification:**
<p>I used Greedy Search because is a simple and objective way to reach the goal.</p>
