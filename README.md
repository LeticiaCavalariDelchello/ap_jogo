# Forest Adventure

## Sobre o Projeto

**Forest Adventure** é um jogo 2D desenvolvido em Python como parte da atividade prática da disciplina **Linguagem de Programação Aplicada**. O objetivo desta atividade é criar um jogo jogável, utilizando bibliotecas gráficas e seguindo os princípios do desenvolvimento de jogos.

## Tecnologias Utilizadas

- **Python**
- **Pygame** 
- **Bibliotecas auxiliares**

## Como Jogar

1. Baixe o repositório ou clone usando:
   ```sh
   git clone https://github.com/LeticiaCavalariDelchello/ap_jogo.git
   ```
2. Instale as dependências necessárias:
   ```sh
   pip install -r requirements.txt
   ```
3. Execute o jogo:
   ```sh
   python main.py
   ```

## Build para Windows

Para gerar um executável do jogo:

1. Certifique-se de ter o **PyInstaller** instalado:
   ```sh
   pip install pyinstaller
   ```
2. Gere o executável:
   ```sh
   pyinstaller --onefile --windowed main.py
   ```
3. Copie os assets (imagens, sons etc.) para a pasta do executável gerado, mantendo a hierarquia de diretórios.

## Estrutura do Projeto

```
ForestAdventure/
├── asset/         # Contém imagens, sons e outros recursos
├── code/            # Contém o código-fonte do jogo
│   ├── Background.py     # Classe do Background do jogo
│   ├── Const.py          # Arquivo de Constantes do jogo, para ser mais fácil de alteração
│   ├── DBProxy.py        # Classe do Banco de Dados
│   ├── Enemy.py          # Classe dos inimigos
│   ├── EnemyShot.py      # Classe dos tiros dos inimigos
│   ├── Entity.py         # Classe das entidades
│   ├── EntityFactory.py  
│   ├── Game.py           # Classe do jogo
│   ├── Level.py          # Classe dos níveis do jogo
│   ├── Menu.py           # Classe do menu do jogo
│   ├── Player.py         # Classe dos jogadores
│   ├── PlayerShot.py     # Classe dos tiros dos jogadores
│   ├── Score.py          # Classe da pontuação do jogo
├── DBScore               # Banco de Dados da pontuação do jogo
├── main.py               # Arquivo principal do projeto
├── README.md             # Documentação do projeto
├── requirements.txt      # Dependências do projeto

```

## Licença

Este projeto é apenas para fins acadêmicos e não possui fins comerciais.

---

Desenvolvido por Leticia Cavalari Delchello para a disciplina de **Linguagem de Programação Aplicada**.


