# Automação de Preenchimento de Formulário com PyAutoGUI

Este projeto automatiza o login em um site e o preenchimento de um formulário utilizando a biblioteca [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) e dados extraídos de um arquivo CSV.

## Tecnologias Utilizadas

- **Python 3.x**: Linguagem de programação utilizada para o desenvolvimento do script.
- **PyAutoGUI**: Biblioteca para automação de interface gráfica que permite controlar o mouse e o teclado.
- **Pandas**: Biblioteca para manipulação e análise de dados, utilizada para ler arquivos CSV.

## Bibliotecas Utilizadas

### 1. PyAutoGUI

- **Descrição**: Permite automatizar ações de mouse e teclado, como clicar, digitar e rolar a tela.
- **Instalação**:
  ```bash
  pip install pyautogui

### 2. Pandas

- **Descrição**: Usada para manipular dados de forma eficiente, especialmente com tabelas, como arquivos CSV.
- **Instalação**:
  ```bash
  pip install pandas
  
 ### 3. Como Funciona o Script

  - Abertura do Navegador e Login;
  - Leitura do Arquivo CSV;
  - Preenchimento do Formulário.

### 4. Capturando a Posição da Tela
Para capturar a posição do mouse na tela, você pode usar o seguinte arquivo Python chamado `pegar_posicao.py`.

#### Explicação do `pegar_posicao.py`
- `time.sleep(5)`: O script aguarda 5 segundos, permitindo que você mova o cursor para a posição desejada na tela.
- `pyautogui.position()`: Esta função retorna a posição atual do cursor em coordenadas (x, y). Você pode usar essas coordenadas em outros scripts para clicar em locais específicos na tela.

### Considerações Finais
- **Ajustes de Coordenadas**: As coordenadas utilizadas para clicar nos campos do formulário podem precisar ser ajustadas de acordo com a resolução da tela e o layout do site.
  
  

