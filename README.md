---- Projeto: Controle de LEDs e Matriz 5x5 com RP2040 ----

Descrição do Projeto
Este projeto implementa um sistema de controle de LEDs e uma matriz de LEDs WS2812 utilizando a placa BitDogLab com RP2040. O sistema emprega interrupções, debouncing via software e exibição de números de 0 a 9 na matriz de LEDs.

---- Funcionalidades Principais:

- Exibição de números de 0 a 9 em uma matriz de LEDs WS2812 (5x5).
- Alterar o número exibido ao pressionar os botões físicos (Botão A/B).
- Aplicar debouncing via software para evitar leituras incorretas dos botões.
- Piscar continuamente um LED vermelho 5 vezes por segundo.

---- Tecnologias Utilizadas

- C
- Pico SDK
- Interrupções (IRQ)
- GPIO (RP2040)
- WS2812 (LEDS)

---- Objetivos

- ✅ Compreender e implementar interrupções no RP2040.
- ✅ Aplicar debouncing via software para evitar múltiplos acionamentos.
- ✅ Controlar LEDs individuais e matrizes WS2812.
- ✅ Criar um projeto funcional combinando hardware e software.

---- Hardware Utilizado

- Placa: BitDogLab com RP2040
- Matriz de LEDs: WS2812 (5x5)
- LED RGB: GPIOs 11, 12 e 13
- Botão A: GPIO 5
- Botão B: GPIO 6

---- Funcionalidades Detalhadas

1. Piscar o LED vermelho.
2. Botão A: Incrementa o número exibido na matriz.
3. Botão B: Decrementa o número exibido na matriz.
4. Matriz WS2812: Exibe os números de 0 a 9.

---- Extras

- O uso de interrupções garante uma resposta rápida e eficiente aos botões.

---- Demonstração do Projeto
🎥 Vídeo do Projeto: [link]
