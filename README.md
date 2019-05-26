# DevopsFinal
<p>
O problema de negócio a ser automatizado com o pipeline acima é o seguinte:
</p>
<p>
O João é um caixeiro viajante que tem clientes em cinco cidades, que abreviamos por A, B, C, D e E. Ele precisa de planear uma viagem de negócios com cidade de partida e de destino final A (a cidade onde mora), passando por cada uma das restantes quatro cidades precisamente uma vez. O grafo abaixo representa o custo de cada viagem (em qualquer um dos sentidos) entre cada par de cidades.
</p>
<img src="https://i.ibb.co/7vvSTdR/grafo.png"/>
<p>
Qual o percurso mais barato para esta viagem do João? Por outras palavras, pretendemos encontrar um ciclo Hamiltoniano ótimo no grafo dado (isto ́e, um ciclo Hamiltoniano cuja soma do peso das arestas é mínimo). 
Um detalhamento maior do problema e orientações para solução são apresentados aqui:
https://en.wikipedia.org/wiki/Travelling_salesman_problem
</p>
Requisitos da Entrega:
<ul>
<li> Implementar o algoritmo manualmente em Java, C#, PHP, Python ou JS. Não é permitido usar bibliotecas que implementam esse algoritmo.</li>
<li> Criar automação de testes de unidade com cobertura de 100%</li>
<li> Possuir cinco experimentos de Engenharia do Caos com o Gremlim (https://principlesofchaos.org) </li>
<li> Contemplar todas as ferramentas citadas na página 1</li>
<li> Todo o código fonte e o código do pipeline devem ser disponibilizado no GitHub</li>
<li> O seu código deve rodar em ambiente Linux ou Windows.</li>
</ul>
Requisitos Opcionais:
<ul>
<li> Você pode incluir outras ferramentas além das ferramentas citadas na página 1.</li>
<li> Abordagens adicionais de testes podem ser usadas tais como TDD ou BDD.</li>
</ul>
