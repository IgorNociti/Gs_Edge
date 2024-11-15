# Gs_Edge
integrantes: Henrique Maciel Rodrigues / 559628 ; Igor Pereira Nociti / 560225 ; Pedro Paulo Sabino / 559578; Sala: 1ESPS
Link do projeto: https://www.tinkercad.com/things/0Txy9VUrnHi-gs-painel-solar/editel
Link do video: https://youtu.be/S7EHCU_DAPQ


Controle de Servo com LDRs
Este projeto utiliza um Arduino para controlar um micro servo motor com base na leitura de dois sensores LDR, permitindo que o servo se mova de acordo com a intensidade de luz detectada, usamos o Tinkercad para simular o projeto, usando a linguagem c++. Visando que no "mundo real", o servo motor irá servir para inclinar o painel solar para a direção do sol ideal, assim conseguindo aproveitar 100% do painel solar.


📋 Pré-requisitos
Nesse projeto utilizamos:

Arduino IDE instalado
Um micro servo motor
Dois LDRs (resistores dependentes de luz)
Resistores de 10kΩ
Fios de conexão e uma protoboard
Um Arduino (como o Arduino Uno)
🔧 Instalação
Para que o código funcione você precisa:

Fazer o upload do código servo_ldr.ino para o seu Arduino.
Conecte os componentes:

Conecte os LDRs e os resistores no Arduino Uno.
Conecte o micro servo aos pinos indicados.
Repita os passos acima até concluir a montagem.

Exemplo de conexão:
Pino A0 → LDR esquerdo (com resistor para GND)
Pino A1 → LDR direito (com resistor para GND)
Pino 5 → Fio de sinal do micro servo
Pino 5V → Fios de alimentação dos LDRs e do servo
GND → Conectado aos resistores e ao servo
⚙️ Executando os testes
Para verificarmos se os LDRs estavam dando certo, printamos eles no Serial, assim sabendo a luminosidade de cada lado.

🔩 Análise de testes de ponta a ponta
Os testes verificam se o servo responde corretamente às diferenças de luminosidade detectadas pelos LDRs. Isso ajuda a garantir que o projeto está sensível a variações de luz conforme o esperado.

🛠️ Construído com
Arduino IDE - Ambiente de desenvolvimento
Componentes eletrônicos como LDRs e micro servo motor
Tinkercad - Ferramenta de simulação
Código Fonte - C++



