# Programação concorrente - Comunicação entre processos usando threads 

<p> Nesse trabalho foi implementado o modelo cliente servidor para a comunicação sincrona entre processos distintos. O Cliente manda solicitações com operador e operandos no seguinte modelo "Operador:operando1:operando2". O servidor por sua vez recebe a mensagem, pocessa o calculo matemático e manda a resposta de volta. Porém o servidor suporta multi-threads, dessa forma um cliente não precisa esparar o processamento do outro pois cada um trá seu processamento em uma thread separada.</p>
