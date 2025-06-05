# ♟Desafio de Xadrez

Este projeto é uma simulação em C que utiliza **estruturas de repetição**, **funções recursivas** e **lógica de movimentação de peças de xadrez** para explorar os limites computacionais do jogo. O código é dividido em três níveis: **Novato**, **Aventureiro** e **Mestre**.

---

## Níveis do Desafio

### 🏅 Nível Novato
Neste nível, utilizamos estruturas de repetição para simular o movimento das peças básicas:

- **Bispo**: 5 casas na **diagonal superior direita**  
- **Torre**: 5 casas para a **direita**  
- **Rainha**: 8 casas para a **esquerda**

**Saída esperada:**
```
Cima + Direita
Cima + Direita
Cima + Direita
Cima + Direita
Cima + Direita
Direita
Direita
Direita
Direita
Direita
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
```

---

### 🏅 Nível Aventureiro
Neste nível, movimentamos o **Cavalo** em formato **L**, utilizando **loops aninhados**, sendo obrigatório o uso de `for` e `while`.

- **Movimento em L**: Baixo + Esquerda (em dois passos)

**Saída esperada:**
```
Baixo
Esquerda
```

---

### 🥇 Nível Mestre
Aqui, o desafio é elevado:

- Movimentos do **Bispo**, **Torre** e **Rainha** são implementados com **funções recursivas**
- O **Cavalo** realiza seu movimento em L com **múltiplas condições**, `break` e `continue` (aplicável em extensões)
- Reforça lógica avançada e uso profissional de estruturas de controle

**Saída esperada:**
```
Movimento Recursivo - Bispo:
Cima + Direita
Cima + Direita
Cima + Direita
Cima + Direita
Cima + Direita

Movimento Recursivo - Torre:
Direita
Direita
Direita
Direita
Direita

Movimento Recursivo - Rainha:
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda

Movimento Avançado - Cavalo:
Cima
Direita
```

---

## Estrutura do Projeto

- `main()` → Fluxo principal
- `moverBispoRecursivo()` → Função recursiva para o Bispo
- `moverTorreRecursiva()` → Função recursiva para a Torre
- `moverRainhaRecursiva()` → Função recursiva para a Rainha
- `moverCavaloL()` → Loop aninhado com `for` e `while`
- `moverCavaloLAvancado()` → Lógica com múltiplas condições e `break`

---

## Como Executar

1. Compile o código com o GCC:
   ```bash
   gcc -o xadrez desafio_xadrez.c
   ```

2. Execute:
   ```bash
   ./xadrez
   ```

---

## Requisitos Atendidos

### Funcionais
- Entrada via variáveis internas e constantes
- Uso de estruturas de repetição (`for`, `while`, `do-while`)
- Saída clara com `printf("Direção\n")`

### Não Funcionais
- **Performance**: execução sem atrasos
- **Documentação**: código comentado e de fácil leitura
- **Manutenibilidade**: nomes descritivos e organização modular

---
