# 🚦Gerenciador-de-Semaforo

Este projeto (em construção) tem como objetivo controlar o funcionamento de semáforos usando sensores ultrassônicos (HC-SR04). 
O sistema utiliza sensores para medir a distância de objetos à frente de cada semáforo, 
ajustando a cor dos LEDs (vermelho, amarelo, verde) com base na proximidade dos obstáculos. 
Os sensores são capazes de detectar a distância e, dependendo do valor obtido, os LEDs são acionados para indicar o estado do semáforo (sinalizando se há um objeto muito próximo, 
uma distância média ou segura).

## 📄 Sobre o projeto
O projeto foi originalmente escrito por outro grupo, porém em um sorteio, foi designado para mim e minha dupla implementarmos exatamente o que foi escrito. Durante o processo, seguimos fielmente a lógica proposta, adaptando o código para garantir que a funcionalidade planejada fosse atingida com os componentes e hardware disponíveis.

## 🛠 Componentes utilizados
- Placa ESP32
- 4 Sensores Ultrassônicos HC-SR04
- 12 LEDs (Vermelho, Amarelo, Verde)
- Resistores para limitar corrente nos LEDs
- Fios de conexão e protoboard
