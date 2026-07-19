#  Dungeon Minotauro

Um jogo de aventura em **Swift**, totalmente em modo texto, onde você explora uma dungeon repleta de criaturas perigosas e enfrenta o poderoso **Minotauro**.

---

##  Sobre o Jogo

Dungeon Minotauro é um RPG simples inspirado em mecânicas de rolagem de dados como D20.  
O objetivo é explorar salas, derrotar inimigos, melhorar seu ataque e chegar ao grande chefe da dungeon.

Você poderá:

- Explorar a dungeon em quatro direções.
- Enfrentar inimigos usando rolagens de dado.
- Sofrer críticos, dar críticos ou falhar miseravelmente.
- Fugir usando testes contra o inimigo.
- Aumentar seu ataque ao derrotar criaturas.
- Enfrentar o **Minotauro** e vencer o jogo!

---

##  Como Jogar

Durante o jogo, você usará comandos de texto:

###  Durante o combate
| Ação | Comando |
|------|---------|
| Atacar | `atacar` |
| Fugir | `fugir` |

###  Movimentação
| Direção | Comando |
|---------|----------|
| Norte | `norte` |
| Sul | `sul` |
| Leste | `leste` |
| Oeste | `oeste` |

###  Sair do jogo

###  Sistema de Combate (D20)
- **20** → Acerto crítico (dano dobrado)
- **1** → Falha crítica (inimigo causa dano extra)
- Valores normais → ataque comum

Ao derrotar inimigos (exceto o boss), seu ataque aumenta em **+1**.

---

##  Estrutura da Dungeon

As salas presentes no jogo:

- **Entrada da Dungeon**
- **Corredor Sombrio**
- **Sala das Armas**
- **Túnel das Sombras**
- **Anticâmara do Minotauro**
- **Centro da Dungeon** (boss)

Cada sala possui:

- Nome  
- Descrição  
- Direções disponíveis  
- Um inimigo (opcional)

---

##  Inimigos

Os inimigos presentes são:

-  **Goblin**
-  **Esqueleto**
-  **Aranha**
-  **Sombra**
-  **Minotauro** (chefe final)

Cada um com vida, ataque e bônus de fuga próprios.

---

##  Como Executar o Projeto

###  Pelo Xcode
1. Abra o projeto.
2. Certifique-se de que o arquivo `main.swift` está na *target* ativa.
3. Clique em **Run**.

###  Pelo Terminal
Se você tiver apenas o arquivo:

```sh
swift main.swift
