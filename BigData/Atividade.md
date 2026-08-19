1. A solução seria várias máquinas trabalhando em cluster.
2. Os dados seriam divididos em pedaços menores, como blocos.
3. Cada máquina leria os dados por partes, em blocos, assim evitando o estouro da memória.
4. Uma máquina receberia apenas os dados úteis e já processados, essa máquina somaria e faria todo o processamento final para mostrar os dados esperados.

Desafio extra: A solução seria pegar todos o trabalho que essa máquina deveria fazer e redistribuir para as demais máquinas, ou ter uma máquina extra para prevenir este tipo de situação
