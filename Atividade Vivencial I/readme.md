# 🎨 Desenhando Triângulos com OpenGL

## Como Executar

Este programa foi desenvolvido e testado em uma máquina Linux com o vscode, portanto o passo a passo para execução será para uma máquina com as mesmas especificações. 

### Pré-requisitos (Linux - Ubuntu/Debian)

Certifique-se de que você tenha as bibliotecas necessárias instaladas:

```bash
sudo apt update
sudo apt install build-essential libglfw3-dev libglew-dev libglm-dev
```
### Compilação

``` bash
g++ main.cpp -o triangulos -lglfw -lGLEW -lGL
```

### Execução

``` bash
./triangulos
```