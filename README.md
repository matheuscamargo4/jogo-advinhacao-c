# Jogo de Adivinhação em C

Este projeto é um simples jogo de adivinhação feito em C. O jogador deve adivinhar um número secreto gerado aleatoriamente. Há três níveis de dificuldade disponíveis: Fácil, Médio e Difícil.

```bash
      P  /_\  P                              
     /_\_|_|_/_\                            
 n_n | ||. .|| | n_n          Bem vindo ao    
 |_|_|nnnn nnnn|_|_|      Jogo de Adivinhação!
|"  |  |_|  |"  " |                         
|_____| ' _ ' |_____|                         
      \__|_|__/                              
```

## Como jogar

1. Ao iniciar o jogo, escolha o nível de dificuldade.

2. Você terá um número de tentativas com base no nível escolhido:
   - **Fácil:** 20 tentativas
   - **Médio:** 15 tentativas
   - **Difícil:** 6 tentativas
3. O objetivo é adivinhar o número secreto entre 0 e 99.

4. A cada tentativa, o jogo indicará se o número secreto é maior ou menor que o número chutado.

## Pré-requisitos

- GCC (ou outro compilador C)

## Compilar o jogo

Para compilar o jogo, execute o comando:

```bash
gcc -o adivinhacao adivinhacao.c
```
## Executar o jogo

Após compilar o jogo, execute-o com:

```bash
./adivinhacao
```
