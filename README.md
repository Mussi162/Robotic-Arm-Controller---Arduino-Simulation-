# 🤖 Robotic-Arm-Controller---Arduino-Simulation-

 Esse projeto apresenta um Braço Robótico controlado por arduino. 
 Cada articulação é manipulada em tempo real (base, braço, antebraço e garra) através de um potenciômetro.
 A simulação permite que a gente possa testar vcontrole de servo motor antes de passar para o projeto real.
 -

 🛠️ Tecnogia e Ferramentário
 * Arduino UNO (ou equivalente)
 * Biblioteca Servo.h
 * Ambiente de simulação (TinkerCAD nesse em esoecífico)
 * 4 servomotores simulados
 * 4 potenciômetros simulados
---

📌 Descrição Geral:
O sistema utiliza 4 servomotores base, braço, antebraço e garra. 
Cada servoi é controlado por um potenciômetro com movimentos suaves.
A logica persiste em leitura do valor enviados dos pinos analógicos que é convertido em ânculos entre 0° e 180° usando map() e enviando ao respectivo servo.
