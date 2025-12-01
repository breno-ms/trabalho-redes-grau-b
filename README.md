# Trabalho de Redes de Computadores - Simulação de Sistemas de Comunicação Digital

Este repositório contém um trabalho acadêmico desenvolvido para a disciplina de Redes de Computadores. O objetivo principal do trabalho é simular a comunicação digital em um canal sujeito a diferentes tipos de ruído, utilizando diversos métodos de codificação, modulação e técnicas de transmissão.

## Descrição

O trabalho simula diferentes esquemas de codificação, modulação e tipos de ruído em um sistema de comunicação digital. Ele utiliza a Taxa de Erro de Bit (BER) como métrica de desempenho para comparar os efeitos de diversas combinações dessas técnicas em diferentes condições de SNR (Razão Sinal/Ruído).

### Funcionalidades

- **Codificação**: Implementação de codificadores como Manchester, AMI, NRZ e RZ.
- **Modulação**: BPSK, QPSK, 8PSK, 16-QAM.
- **Ruído**: Ruído AWGN (Aditivo Branco Gaussiano), Ruído Impulsivo e Ruído Rayleigh.
- **Simulação de Desempenho**: Cálculo da Taxa de Erro de Bit (BER) e geração de gráficos comparativos.
- **Gráficos**: Visualização das simulações para diferentes combinações de modulação, codificação e ruído.

## Como Usar

### Pré-requisitos

Este trabalho foi desenvolvido em Python e utiliza as seguintes bibliotecas:
- `numpy`
- `pandas`
- `matplotlib`

Você pode instalar as dependências necessárias utilizando o comando:

```bash
pip install numpy pandas matplotlib
