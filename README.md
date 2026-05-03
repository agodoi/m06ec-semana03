# Atendimento do Professor

## Terças e quintas. Professor de horário parcial. Nesses 2 dias, podem contar comigo!

# Semama 03 - Semicondutores e Diodos

## Impactos no seu Projeto

* Proteção dos seus circuitos
* Construção de fontes retificadoras

# 1. Introdução

A eletrônica moderna é construída com base em componentes semicondutores, sendo os **diodos** um dos dispositivos fundamentais em diversos circuitos.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/atlas1.png" width="300">

Eles desempenham um papel essencial no controle do fluxo de corrente elétrica, permitindo sua passagem em apenas uma direção e bloqueando-a na outra.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo2.png" width="300">

## Comportamento do Diodo

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo1.gif" width="300">

* Quando o positivo da bateria está conectado no positivo do diodo, dizemos que o diodo está polarizado diretamente e por isso, ele está conduzindo a corrente.

* Quando o positivo da bateria está conectado no negativo do diodo, ele está polarizado reversamente e por isso, ele está conduzindo praticamente nada.


## Do que é feito o Diodo?
## Como é o seu comportamento?
## Para que serve?
# Vamos de Kahoot

## Prática (1) - Dominando o Oscilocópio

O Oscila server para você analisar sinais no domínio do tempo. Sua tela é organizada em X e Y, sendo X o eixo dos tempos, em Y o eixo de Volts.

Os botões mais usados:

* **AUTO** serve para ajustar o sinal automaticamente no centro da tela
* **CH1** serve para habilitar/desabilitar o canal 1. Você pode ligar/desligar o canal 1 pressionando esse botão por 1 ou 2s
* **CH2** serve para habilitar/desabilitar o canal 2.
* **F1** serve para habilitar/desabilitar o tipo de acomplamento do sinal. DC serve para ler sinais contínuos, AC serve para ler sinais contínuos e alternados, GND serve para aterrar o sinal de entrada. Você faz isso calibrar o sinal no meio da tela manualmente
* **SET TO ZERO** serve para centrar os sinais no meio da tela de forma automática
* **SCALE VOLTS** serve para configurar quanto vale 1 quadradinho da tela no eixo vertical
* **SCALE SEC** serve para configurar quanto vale 1 quadradinho da tela no eixo horizontal

Siga as orientações do professor para fazer a sua primeira medição no oscilas.


## Prática (2) - Dominando o Gerador de Sinais

Esse equipamento serve para você gerar sinais senoidais, onda quadrada e onda triangular, com diversas frequências e amplitudes.

Os botões mais usados são todos :)

* **RANGE (Hz)/GATE** server para você escolher a frequência do sinal de saída. Exemplo: selecionando **X2k** você vai ter frequência de **0 até 2kHz**. Se pressionar **X20k**, você terá de **0 até 20k Hz**
* **FUNCTION**, você escolhe o tipo de sinal. Os possíveis são: senoidal, quadrado e triangular.
* **ATT**, você aplica uma redução do sinal de saíde de 20dB ou 40dB
* **FREQUENCY**, você ajusta a frequência do sinal
* **AMPL**, você ajusta a amplitude do sinal. Esse gerador libera de 0 até 10.9Vp ou 21,8Vpp

## FAÇA UMA CÓPIA DESSE [RELATÓRIO](https://docs.google.com/document/d/1LkbReoAI1K1JSjQOJgL4Bmv3HBXjFxqiyweYZJd4Ekg/edit?usp=sharing) PARA O SEU GOOGLE DRIVER E PREENCHA COM AS MEDIÇÕES QUE SE PEDE.


## Prática (3) - Teste de Condutividade do Diodo

### 1) Configuração do Multímetro:

* Ajustar o multímetro para o modo "Teste de Diodo" ou medição de tensão DC. Quando você está na escala de Diodo, o resultado na tela é sempre Volts.
* Medição do Diodo:
*    Conectar as pontas de prova do multímetro nos terminais do diodo:
*    Vermelho no ânodo e preto no cátodo (polarização direta).
*    Preto no ânodo e vermelho no cátodo (polarização reversa).

### Responda:

* (a) O que aconteceu com o valor da tensão na polarização direta?
* (b) O que aconteceu com o valor da tensão na polarização reserva?
* (c) O que aconteceu com o sinal sonoro na polarização direta?
* (d) O que aconteceu com o sinal sonoro na polarização reserva?

## Prática (4) - Teste de Retificação do Diodo (Retificador de Meia Onda)


Monte o circuito abaixo no **Tinkercad** usando 1 diodo **(D)** 1N4007, resistor **(R)** de 1k ohms e um protoboard pequeno.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/oscilas-01.png" width="600">

E monte esse mesmo circuito na prática.

### Configuração do osciloscópio do Tinkercad:

* No desenho há 2 telas de osciloscópio, então adicione as duas na sua tela;
* Configure o SEC/DIV (Tempo por divisão) de cada oscilas para **1ms** 

### Configuração do Gerador de Sinais no Tinkercad:

* Freq. em 300Hz
* Amplitude: 10Vp
* Deslocamento: 0V
* Função: seno

### Responda:

(a) Usando o multímetro de bancada, coloque na escala 20V~ (tensão alternada em 20 volts) e confira se você tem 10V~ na saída do gerador de sinais. Ajuste o knob **AMPL** para **MIN** ou **MAX** até encontrar os 10V~.

(b) Usando o multímetro de bancada na mesma escala 20V~, meça a tensão sobre o **R**. Quanto você encontrou?

(c) Usando o multímetro de bancada, mas agora na escala 2V~, meça a tensão sobre o **D**. Quanto você encontrou?

(d) Agora, comprove matematicamente os valores que você mediu.

(e) Diminua o valor de **AMPL** do gerador de sinais para abaixo de 0,7V~ (use o multímetro de bancada para conferir o valor).

(f) Repita as medições de (c) e (d). O que você conclui?

(g) Volte o valor de AMPL para o máximo, e vamos analisar o comportamento de retificação do D. Compare na sua tela do oscilas, o sinal senoidal original e o retificado, tentando colocar os dois sinais um sobre o outro na sua tela, mexendo no botão **POSITION VERTICAL**. Consegue verificar que metade da onda não está presente no **R**?

## Prática (5) - Medindo corrente elétrica

Nessa aula, vamos confirmar na prática, como se mede corrente elétrica de um circuito.


Insira o multímetro em série no seu circuito Diodo e Resistor para medir o Itotal.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/oscilas-02.png" width="600">



### LEMBRE-SE QUE ESSA MEDIÇÃO PODE QUEIMAR O MULTÍMETRO SE NÃO FEITO CORRETAMENTE!!! Mas não tenha medo...


* Meça a corrente total do circuito retificador meia onda.

Responda:

* (a) A corrente que passa pelo **D** é igual a que passa no **R**?
* (b) Vamos conferir se a corrente está dentro dos limites especificados no datasheet do Diodo 1N4007. Acesse esse site [ALL DATASHEET](https://www.alldatasheet.com/) e busque o PDF do 1N4007, faça o download, e busque pelo valor **Average Rectified Output Current**. Esse é o valor máximo de Itotal que o D suporta na polarização direta.
* Um dado importante: o valor da corrente que você está medindo no multímetro não é real. Por que?

* Porque o multímetro só entende sinais senoidais limpos e perfeitos. O sinal que você está medindo é pulsante e não senoidal.


## Prática (6) - Montando um Retificador de Onda Completa

É muito importante você entender o comportamento das correntes e tensões do circuito abaixo para dominar o funcionamento das fontes de qualquer dispositivo eletrônico.

* Monte o circuito abaixo com **MÁXIMO DE CUIDADO!** SE FECHAR CURTO NO SECUNDÁRIO DO TRAFO, VAI FAZER ESTRAGO
* No lugar da fonte, ligue os fios marcados como secundário. O trafo não tem polaridade nos fios. Ambos fios são iguais.
* Os 4 diodos são 1N4007
* O capacitor é eletrolítico de 2.200uF / 25V
* O regulador de tensão é o 7805
* O resistor é de 1k ohms (marrom preto vermelho)

<img src="https://github.com/agodoi/m05-semana04/blob/main/imgs/circuito-retificador-final.png" width="600">

Após a montagem...

### Responda:

**(a)** Insira o multímetro na escala de corrente A~ entre o secundário e uma das entradas da ponde de diodo para medir a corrente total. Quanto tem de corrente total?

**(b)** Insira o multímetro na escala de tensão no secundário do trafo, na escala de V~ para medir a tensão total de entrada. Quanto tem de tensão no secundário?

**(c)** Coloque o CH1 do oscila nos terminais do secundário do trafo e observe a forma de onda. Qual o tipo de onda você está observando?

**(d)** Coloque o CH2 do oscila nos terminais do R e observe a forma de onda. Qual o tipo de onda você está observando?

**(e)** Remova o C do circuito e observe a forma de onda. Qual o tipo de onda você está observando?

**(f)** Volte o C para o circuito. Insira o multímetro na escala de tensão V~ entre os terminais do R. Quanto tem de tensão?

**(g)** Insira o multímetro na escala de tensão V= após o regulador de tensão. Quanto tem de tensão?

