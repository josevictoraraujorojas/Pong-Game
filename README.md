# Jogo de Pong

## Descrição

Este projeto é uma recriação do clássico jogo **Pong**, desenvolvido utilizando HTML, CSS e JavaScript. O jogo é jogado por dois jogadores, cada um controlando uma raquete, com o objetivo de marcar pontos ao fazer a bola passar pela raquete adversária.

---

## Funcionalidades

- **Jogo para dois jogadores**:
  - **Jogador 1** controla a raquete com as teclas **W** (subir) e **S** (descer).
  - **Jogador 2** controla a raquete com as teclas **Seta para cima** e **Seta para baixo**.
- **Pontuação**: Cada jogador ganha pontos quando o adversário deixa a bola passar.
- **Movimento da bola**: A bola se move na diagonal e muda de direção ao colidir com as raquetes ou bordas.
- **Interface gráfica**: Elementos desenhados dinamicamente no canvas do HTML.

---

## Tecnologias Utilizadas

- **HTML**: Estrutura do canvas para renderizar o jogo.
- **CSS**: Estilização básica.
- **JavaScript**: Controle da lógica do jogo, incluindo:
  - Movimentação dos jogadores.
  - Colisões entre bola, raquetes e bordas.
  - Atualização da pontuação.
  - Controle do loop de animação.

---

## Estrutura do Projeto

```plaintext
.
├── index.html          # Estrutura principal do jogo
├── css/
│   └── estilo.css      # Estilização básica
├── javascript/
│   ├── Bola.js         # Classe para controle da bola
│   ├── Direcao.js      # Classe para gerenciar direções
│   └── Jogador.js      # Classe para controle dos jogadores
└── script.js           # Código principal do jogo
```
