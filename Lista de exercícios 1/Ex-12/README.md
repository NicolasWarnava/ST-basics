12. Desenvolver um sistema de gerenciamento de uma bomba de circulação de produto
químico, em três tanques. Existe um LSH (sensor de nível alto) e um LSL (sensor de nível
baixo) para cada tanque. Para ligar a bomba (K2), nenhum dos tanques deve estar com o
nível alto e o operador deve dar partida por um botão B1, podendo desligá-la pelo botão
B2. Se o nível dentro de um dos tanques subir ao limite superior, a bomba desliga. Se o
nível de um dos tanques atingir o limite mínimo, e nenhum dos outros tanques estiver no
limite máximo, deve ser ligada a bomba K2 e ligada a saída de alarme visual e sonoro
(K1), ficando esse alarme ativo por 5 segundos. Crie uma estrutura para de dados para
os tanques, contendo uma variável de medição do nível de concentração do produto
(REAL) e duas variáveis de contagem (INT) dos eventos de nível máximo atingido, nível
mínimo atingido (ambos de cada tanque), e de acionamentos da bomba (do sistema), crie
um array contendo as estruturas de dados dos três tanques. A leitura de concentração
para os três tanques é feita por sensores/transmissores analógicos (AT) que utilizam uma
única entrada analógica (valor de 0,00UI a 50,00UI, fundo de escala 10.000) selecionada
a cada 5 segundos para a leitura de cada tanque e respectiva atualização do dado no
array de tanques (intervalo de 5s, mede tanque 1, intervalo de 5s, mede tanque 2,
intervalo de 5s, mede tanque 3, e assim sucessivamente). Exibir na tela principal da IHM
o status da bomba, do alarme e da medição atualizada dos três tanques), em uma
segunda tela, exibir os contadores de eventos atualizados dos três tanques. Ao ser
reiniciado o CLP, todas as variáveis retornam ao valor inicial “zero”.

 Identificar na figura os endereços de entradas e saídas utilizadas.
