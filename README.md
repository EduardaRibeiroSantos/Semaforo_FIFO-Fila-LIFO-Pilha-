# Simulação de Cruzamento com Estrutura de dados FIFO (Fila) & LIFO(Pilha)

Simulação via terminal de um cruzamento entre duas vias, dos quais os carros são liberados através de semáforos em direção a um estacionamento gaveta.

A priori, os carros são distribuidos de maneira aleatória entre as pistas 1 e 2, tendo um intervalo de chegada entre cada carro de 1 a 5 segundos. Após listados os carros, os semáforos funcionam enquanto as pistas não estiverem vazias. Vale ressaltar que o semáforo funciona por 10 segundos, seja na cor verde ou vermelha. Levando em conta que cada carro demora 2 segundos para sair da fila, há um limite de 5 carros por vez enquanto o sinal estiver aberto e, de maneira lógica, quando o semáforo da pista 1 fechar, o sinal da pista 2 irá abrir, assim de maneira sucessiva.

Após todos os carros terem ido em direção ao estacionamento, é sorteado, de forma randômica, um dos cinco carros estacionados para sair do estacionamento. Logo, a execução a pilha é efetuada, visto que para remover o primeiro carro inserido - em um total de 5 - é necessário que os outros 4 anteriores a ele também sejam.

Por fim, os carros removidos do estacionamento voltam para a pista 1.
 
