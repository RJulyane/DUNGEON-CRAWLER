# 🗡️ Dungeon Crawler — O Grande Narrador

> *"Ah, mais um herói. Que surpresa. Que... originalidade."*

---

## 📖 História

Uma voz aparece na tela. Ela te guia pela vila, te apresenta o ferreiro, te ensina os controles.

> *"Pegue a espada. Ou o arco. Ou o cajado. Tanto faz, honestamente."*

Você desce para a masmorra.

Primeiro andar. Você morre no espinho.

> *"Aquele estava bem na sua frente. Impressionante."*

Segundo andar. Um monstro te encurrala.

> *"Fascinante. Você foi em direção a ele. Voluntariamente."*

Terceiro andar. Suas vidas acabam.

> *"Haha. Suas vidas acabaram! Não se preocupe, reiniciei tudo pra você. Sou tão generoso."*

Você chega na sala final.

> *"Parabéns. Você chegou até aqui. Eu deixei, claro — precisava de entretenimento."*
>
> *"Os monstros? Meus. Os espinhos? Meus. O Cristal que você veio buscar? Também meu. Sempre foi."*
>
> *"Mas foi divertido te ver tentar. De verdade."*

O Narrador não quer destruir o reino, não quer poder, não quer nada grandioso. **Ele só quer se divertir.** E você acabou de ser o melhor espetáculo da semana.

> *"Pressione qualquer tecla para jogar de novo. Vai lá. Tenho tempo."*

---

## 👥 Desenvolvedores

| Nome | GitHub |
|------|--------|
| Julyane Ribeiro | [@Rjulyane](https://github.com/Rjulyane) |

---

## 🎮 Como Jogar

### Objetivo
Siga a voz do Narrador. Explore a vila, escolha sua arma, atravesse os 3 andares da masmorra e chegue até o boss final.

Mas cuidado com quem você confia.

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
│   ├── Vila (10×10)
│   │   └── Ferreiro — escolha sua arma
│   ├── 1º Andar — O Vestíbulo (10×10)
│   ├── 2º Andar — As Catacumbas (15×15)
│   └── 3º Andar — A Sala do Narrador (25×25)
│       └── Boss: O Narrador
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
| `Z` | Boss Final — O Narrador |

---

## 🤖 Uso de IA Generativa

Este projeto utilizou IA generativa (Claude, da Anthropic) como ferramenta de apoio nas seguintes situações:

- **Depuração de código:** identificação de bugs e explicação dos erros
- **Dúvidas pontuais:** esclarecimento de comportamentos do C e funções de biblioteca
- **Criação da história:** geração do lore e narrativa do jogo

Todo o código foi compreendido, revisado e é de total responsabilidade da equipe.

---



*Projeto desenvolvido para a disciplina de Algoritmo e Codificação de Sistemas — 2026*
