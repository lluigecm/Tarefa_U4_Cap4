# Controle de Matriz de LEDs 5x5 WS2812 com botões.

## Descrição
O projeto consiste em utilizar a placa BitDogLab para mostrar os algarismos usando a matriz de led WS2812, onde um botão é responsavel por incrementar e o outro por decrementar. O projeto conta com a implementação de IRQ, e também de debounce via software.

## Funcionalidades
O Botões permitem controlar a matriz de LEDs com as seguintes funcionalidades, a partir de IRQ:

- **Botão A**: Incrementa o algarismo atual na matriz de led.
- **Botão B**: Decrementa o algarismo atual na matriz de led.

[Vídeo de Demonstração](https://www.dropbox.com/scl/fi/1abahx1t4q1lqkqf6cuv6/V-deo-02-02-2025-17-55-14.mov?rlkey=mvby1bls2javtrgpoyzu70vwk&st=0s8bot6x&dl=0)

## Como compilar
Para compilar o programa, utilize um compilador C, gerando os arquivos `.uf2` e `.elf`. Siga os passos abaixo:

1. Configure o ambiente de desenvolvimento para o Raspberry Pi Pico.
2. Compile o código utilizando um compilador compatível.

Segue um exemplo do botão de compilação:

![botao compilador](fotos_readme/compilador.png)

## Como executar

1. Plugue sua placa BitDogLab via cabo micro-usb.
2. Ative o modo bootset da placa.
3. Clique no botão Run.

![botao compilador](fotos_readme/compilador.png)

## Requisitos
- Compilador C (gcc ou equivalente).
- Sistema operacional compatível com programas C.
- Extensão Raspberry Pi Pico.
- Placa BitDogLab

### Observação
- Caso queira rodar o código na extensão wokwi, será necessário criar e configurar os arquivos .toml e .json necessários.