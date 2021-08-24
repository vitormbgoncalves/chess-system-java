# ♟ Chess System Java

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [JDK 11](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html): Kit de desenvolvimento para a linguagem Java.
- [IntelliJ IDEA](https://www.jetbrains.com/pt-br/idea/): IDE (Integrated Development Environment) para desenvolvimento Java.

## 💾 Projeto
Este projeto foi desenvolvido com base no curso  *__Java COMPLETO Programação Orientada a Objetos + Projetos__* da [Udemy](https://www.udemy.com/course/java-curso-completo/), ministrado pelo professor [Nelio Alves](https://github.com/acenelio).
Esta aplicação consiste em um jogo simples de Xadrez, que pode ser executado através do terminal. O jogo possui tratamento de erros, programação defensiva (contra bugs), jogadas especiais do xadrez (promoção, roque e en passant) e previsão de movimento das peças.

Peças: Pawn (Peão), Rook (Torre), Knight (Cavalo), Bishop (Bispo), Queen (Rainha) e King (Rei).
|-|

A mecânica do jogo é baseada em **linhas** (_1, 2, 3, 4, 5, 6, 7, 8_) e **colunas** (_a, b, c, d, e, f, g, h_)
- Para **escolher** uma peça é necessário selecionar _primeiramente_ a **coluna** e logo em seguida (sem espaços) selecionar a **linha**, exemplo: **c2**
- Em **Captured pieces** o jogo armazena as peças capturadas.
- O **Turn** exibe o turno (rodada) em que o jogo está.
- **Waiting player** exibe qual é o jogador a jogar a próxima peça.
- **Source** é a origem, ou seja, a peça no qual o jogador irá jogar.
- **Target** é o destino, ou seja, o local no qual o jogador irá mover a peça.
- O jogo possui sistema de **Check** e **CheckMate**

## 💻  Instalacao

1. Clone o projeto através do terminal;

```shell
git clone https://github.com/vitormbgoncalves/chess-system-java.git
cd chess-system-java/src
```

3. Para rodar a aplicação no Linux, execute o código abaixo;

```shell
javac application/Program.java
```

4. Bom Jogo!
