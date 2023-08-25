3. A lixa de uma lixadeira de fios deve ser afiada periodicamente, e para isto o sentido de
rotação do motor deve ser invertido. Para isto, o controle possui duas saídas digitais, uma
que aciona a o motor no sentido de lixamento, outra que aciona o motor no sentido de
afiação. O painel de operação possui um botão de partida e um botão de parada apenas
para operação de lixamento, e o painel de manutenção possui um botão de afia e um de
parada de emergência que atua nos dois modos (lixamento e afiação). (todos são
entradas digitais do CP). O eixo da máquina possui um sensor de rotação (uma entrada
digital do CP, será simulada manualmente), que indica se o eixo está girando (#1) ou
parado (#0). A lógica de acionamento dita que o motor só pode ser acionado quando seu
eixo estiver parado. Caso seja comandado para trocar de direção com o eixo em
movimento, o comando deve efetuar o desligamento do movimento e aguardar novo
comando somente quando o eixo estiver parado. Elabore um programa que implemente
esta lógica. No display da IHM devem ser exibidos o status do motor (‘OPERAÇÃO’ ou
‘AFIAÇÃO’), do sensor de rotação (‘MOTOR GIRANDO’ ou ‘MOTOR PARADO’).
