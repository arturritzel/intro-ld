Exercício 1:
- Um painel apresenta um conjunto de 4 chaves.
- Elabore um aplicativo que acione uma carga (saída digital) sempre que o número de chaves ligadas for par (considere zero como par).
- Elabore primeiramente a tabela-verdade, extraia a expressão e simplifique antes de implementar o programa.
- Utilize as lógicas básicas já estudadas.

Exercício 2:
- Um painel apresenta dois conjuntos de chaves, A e B.
- Cada conjunto é composto por duas chaves, chave 0 e chave 1.
- Desenvolva um aplicativo que acione uma saída, sempre que os dois conjuntos apresentem a mesma combinação.
- Elabore primeiramente a tabela-verdade, extraia a expressão e simplifique antes de implementar o programa.
- Utilize as lógicas básicas já estudadas.
- Exemplo: Se as chave A0 estiver ligada e a chave A1 estiver desligada, a lâmpada só poderá acender se a
chave B0 estiver ligada e a chave B1 estiver desligada.

Exercício 3:
- Implementar um acionamento sequencial onde, após dado comando, a primeira carga é acionada por 5
segundos, desligada e uma segunda carga é ativada por mais 5 segundos e, então, desligada também.
- Após este ciclo, o programa deve poder receber um novo comando e repetir o processo.

Exercício 4:
- Utilizando o teclado da IHM, implemente o comando de duas cargas com acionamento mutuamente
excludente (uma carga só aciona se a outra estiver desligada).
- Utilize duas teclas de acionamento e uma tecla de desligamento.
- Indique através do display da IHM cada tecla e sua respectiva função.

Exercício 5:
- Ler o sinal de uma das entradas analógicas e exibir o valor na IHM.
- Utilize fundo de escala 1000, e exiba o valor em Volts (0,00V a 10,00V com dois algarismos significativos após a vírgula e a unidade de medida).

Exercício 6:
- Elabore uma minuteria (pesquise o que é, caso não saiba), acionável através de um botão (entrada digital), com tempo programável via IHM (variável no formato TIME).
- Tanto o tempo programado quanto o tempo da contagem devem ser exibidos no display da IHM.

Exercício 7:
- Elabore um comando liga-desliga utilizando como comando uma entrada analógica.
- Acione a carga (saída digital) quando a tensão de entrada for igual ou superior a 70% do valor máximo da entrada e desligue a carga quando a tensão de entrada for inferior a 30% do valor máximo.
- Caso um botão do painel (entrada digital), denominado emergência, seja acionado, a carga deve ser desligada e não pode ser acionada por um período de 5 segundos.
- O valor máximo deve ser armazenado em uma variável de programa não volátil, através de um botão da IHM.
- As variáveis de medição, valor máximo e contagem devem ser exibidas no display da IHM.

Exercício 8:
- Elabore um comando liga-desliga utilizando como comando a entrada analógica.
- Acione a carga quando a tensão de entrada for inferior um limite MIN (valor inicial de 4,00 V) e desligue a carga quando a tensão de entrada for superior a um limite MAX (valor inicial de 6,00 V).
- Os valores MAX e MIN devem poder ser editados pela IHM.
- Caso um botão de EMERGENCIA seja acionado a qualquer instante, a carga deve ser imediatamente desligada, e um novo acionamento só poderá ser realizado após o sinal de entrada permanecer, por, no mínimo, 10s em 0V.
- Exiba o valor de tensão lido na IHM, em 3 telas diferentes, utilizando elementos gráficos diferentes (explorar os elementos gráficos disponíveis para as telas da IHM).
- Usar a escala apropriada (duas casas decimais) e com indicação de unidade.
