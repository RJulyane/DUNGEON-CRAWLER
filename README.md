# 🗡️ Dungeon Crawler — A Última Chama de Aetherfall

> *"Não volte sem o Cristal, Kael. Ou não volte."*

---

## 📖 História

O reino de **Aetherfall** viveu séculos de paz graças ao **Cristal da Aurora**, um artefato lendário que mantinha os males das trevas afastados das terras dos homens.

Há três dias, o céu escureceu.

**Malgrath, o Devorador**, acordou nas profundezas da Masmorra de Cinzas e corrompeu o Cristal. As colheitas murcharam, os animais fugiram e os aldeões adoeceram lentamente. Os guerreiros enviados para enfrentá-lo nunca voltaram.

Você é **Kael** — um jovem aventureiro sem fama e sem treinamento formal, criado na pequena vila de **Miravel**. Sem nada a perder, você pega sua arma e desce às profundezas para recuperar o Cristal e salvar o reino.

---

## 👥 Desenvolvedores

| Nome | GitHub |
|------|--------|
| [Seu Nome Aqui] | [@usuario](https://github.com/usuario) |
| [Nome do Colega] | [@usuario2](https://github.com/usuario2) |
| [Nome do Colega] | [@usuario3](https://github.com/usuario3) |

---

## 🎮 Como Jogar

### Objetivo
Explore a vila, escolha sua arma, atravesse os 3 andares da masmorra e derrote **Malgrath** para restaurar o Cristal da Aurora.

### Controles

| Tecla | Ação |
|-------|------|
| `W` | Mover para cima |
| `A` | Mover para a esquerda |
| `S` | Mover para baixo |
| `D` | Mover para a direita |
| `I` | Interagir com objeto à frente |
| `O` | Atacar célula à frente |
| `ESC` | Sair / Voltar ao menu |

### Armas disponíveis

| Arma | Descrição |
|------|-----------|
| ⚔️ Espada | Ataca uma área de 3×2 células à frente |
| 🏹 Arco e Flecha | Ataca em linha reta por 4 células |
| 🪄 Cajado | Ataca todas as 8 células ao redor simultaneamente |

### Vidas
Você possui **3 vidas**. Ao colidir com espinhos ou ser tocado por um monstro, perde 1 vida e a fase reinicia. Ao perder todas, a tela de **Game Over** é exibida.

---

## 🗺️ Estrutura do Jogo

```
Menu Principal
├── Jornada
│   ├── Vila de Miravel (10×10)
│   │   └── NPC Aldric — escolha sua arma
│   ├── 1º Andar — O Vestíbulo Esquecido (10×10)
│   ├── 2º Andar — As Catacumbas Corrompidas (15×15)
│   └── 3º Andar — O Trono das Cinzas (25×25)
│       └── Boss: Malgrath, o Devorador
├── Treinamento
└── Sair
```

---

## 🔣 Símbolos do Mapa

| Símbolo | Significado |
|---------|-------------|
| `^` `v` `<` `>` | Jogador (direção que está olhando) |
| `*` | Parede — bloqueia passagem |
| `#` | Espinho — mata ao passar |
| `k` | Caixa — bloqueia, pode ser destruída |
| `O` | Botão — executa uma ação |
| `D` | Porta fechada — bloqueia passagem |
| `@` | Chave — abre porta fechada |
| `=` | Porta aberta — pode passar |
| `L` | Escada — avança para o próximo andar |
| `X` | Monstro Tipo 1 — movimento aleatório |
| `Y` | Monstro Tipo 2 — persegue o jogador |
| `Z` | Boss Final — Malgrath |

---

## 🤖 Uso de IA Generativa

Este projeto utilizou IA generativa (Claude, da Anthropic) como ferramenta de apoio ao desenvolvimento nas seguintes situações:

- **Depuração de código:** identificação de bugs e explicação dos erros
- **Dúvidas pontuais:** esclarecimento de comportamentos do C e funções de biblioteca
- **Criação da história:** geração do lore e narrativa do jogo

Todo o código foi compreendido, revisado e é de total responsabilidade da equipe. Nenhum trecho foi utilizado sem entendimento prévio de seu funcionamento.

---

## 🛠️ Como Compilar

### Pré-requisitos
- GCC instalado (MinGW no Windows)

### Compilação
```bash
gcc joguitto.c -o joguitto.exe
```

### Execução
```bash
.\joguitto.exe
```

---

*Projeto desenvolvido para a disciplina de Introdução à Programação — 2025*
