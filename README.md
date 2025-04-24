# MEDIDOR DE LUMINOSIDADE

## Componentes 
- 1 LED verde;
- 1 LED vermelho;
- 1 LED amarelo;
- LDR;
- Buzzer;
- Arduino

## Código

1. Para começar nos devemos definir as entradas dos componentes, sendo os LEDs e buzzer digitais e o LDR analógico. Crie duas variáveis:
- Valor LDR
- Luz

<br>

2. Depois defina o tipo de entrada no void setup.

3. Após isso definimos a variável do ldr como o valor da entrada analógica e utilizamos a função *map()* para transformar o valor entre numeros de 0 a 100.

4. Depois fazemos a verificação do nivel de luminosidade utilizando if e else. Se o valor for baixo, liga o LED verde, se for o valor de uma luminosidade ambiente liga o amarelo, se tiver uma luminosidade alta liga o vermelho e se for muito alta, liga o vermelho e o buzzer apita por 3 segundos.

## Links
### Tinkercad: 
https://www.tinkercad.com/things/3Vv0zPxs9nq-exquisite-sango-elzing/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=AEJ2IvzMNMX_ytq1Lmavgh9g_FC6MlVzmet1MU_2xe0

### Vídeo de Explicação:
https://youtu.be/tPVpF7j2aFs?si=hn448DKk2BlqLWa6

## Integrantes do Ambiente Guard:
- Enzo Dourado
- Matheus Victorio
- Vinícius Lugli
- Hugo Copatti
- Lucas Villani
