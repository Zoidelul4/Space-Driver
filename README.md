8# 🛸 Projeto-Mobile - Space Driver

Este projeto é uma recriação do clássico jogo Space Invaders, desenvolvido especificamente para dispositivos móveis utilizando o GameMaker Studio. O jogo mantém a essência do original enquanto adiciona controles otimizados para touchscreen e alguns recursos modernos.

# 👨‍🏫 Professor responsável
Carlos Eduardo Duque Polito

# 🎯 Objetivo do projeto
Recriar o clássico jogo Space Invaders com mecânicas modernas e controles otimizados para dispositivos móveis, utilizando o GameMaker Studio 2.

# ✖️ O que não é planejado para o projeto

Jogo com gráficos 3D complexos

Sistema multiplayer online

Microtransações ou compras dentro do aplicativo

# 👥 Público-alvo
Jogadores casuais e fãs de jogos retrô que desejam uma experiência nostálgica mas adaptada para smartphones modernos.

# 🔨 Requisitos funcionais

Sistema de movimento: Controles touch para mover a nave

Sistema de disparo: Disparo automático

Geração de inimigos: Ondas progressivas de aliens

Sistema de pontuação: Contagem de pontos por inimigos derrotados

Menu de pause: Opção para pausar o jogo durante a partida, funcionando caso salve e saia do jogo tambem 

Seleção de dificuldade: Diferentes níveis de desafio

Sistema de Ranking: Seu Nome e score gravado no rank.

# ☑️ Requisitos não funcionais

Desempenho: 60 FPS em dispositivos Android/iOS medianos

Compatibilidade: Funcionar em versões Android

Otimização: Consumo de bateria eficiente

Controles: Responsivos e otizimados

# 📑 Matrizes de Requisitos

<h2> Matriz de Requisitos Gerais
  
![image](https://github.com/user-attachments/assets/0208ced6-4181-4867-b07e-22a92ebdf8cf)

<h2> Matriz de Requisitos Funcionais

![image](https://github.com/user-attachments/assets/da9f5a58-c9c3-44c5-aee6-76111e0e2476)

# 📱 Mockup do Jogo


# 📊 Estrutura do Projeto

Copy
/Sprites
  - Player
  - Enemies
  - Bullets
  - Backgrounds
/Scripts
  - Movement
  - Shooting
  - EnemyAI
  - GameManager
/Sounds
  - Effects
  - Music
/Rooms
  - MainMenu
  - GameLevels
  - GameOver

# 📖 Dicionário de objetos

obj_player: Entidade controlada pelo jogador

Variáveis: lives, speed, fireRate

obj_enemy: Inimigos básicos

Variáveis: health, points, movementPattern

obj_bullet: Projéteis do jogador

Variáveis: speed, damage

obj_gameController: Controla lógica do jogo

Variáveis: score, level, difficulty

# 🧍 Diagramas UML

- Diagrama de Sequencia
  
![Image](https://github.com/user-attachments/assets/da382ba4-e1ad-47d0-93d7-6e4ea5fabd29)

- Diagrama de Caso de Uso

![Image](https://github.com/user-attachments/assets/4dd8ecc8-1e92-4a3b-b73a-48236731e7ef)

- Diagrama de Componentes

![Image](https://github.com/user-attachments/assets/e3bc00b0-1ef8-4bfd-b26b-6cebe2e0effa)

- Diagrama de Atividade

![Image](https://github.com/user-attachments/assets/b6704cb5-f0ba-4207-b490-f2a046cf0519)

- Diagrama de Classes

![Image](https://github.com/user-attachments/assets/331ca304-2edd-463c-90c2-03a77e086e32)

# 🛢️ Requisitos Técnicos

Resolução: 1080x1920 (adaptável)

Taxa de atualização: 60Hz

Armazenamento: ~50MB (Android/iOS)

# 🧰 Tecnologias Utilizadas

Desenvolvimento: GameMaker Studio

Programação: GML (GameMaker Language)

Arte: Piskel Art (Pixelart)

Áudio: Áudios encontrados na internet (efeitos sonoros)

Atualização do projeto: GitHub

# ⚠️ Limitações conhecidas

Não suporta modelos de telefone muito antigos

Limitação de controles


# 💻 Desenvolvedores
<h2> Miguel Luís Gomes de Melo, Luís Gustavo Novaes dos Santos <h2>
