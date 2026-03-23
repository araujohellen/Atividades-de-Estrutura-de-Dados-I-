---

# 🧩 20 Perguntas — Torre de Hanói em Java

## 🧠 Parte 1 – Conceitos Gerais

1. O que representa o problema da Torre de Hanói?   
2. Quem foi o criador da Torre de Hanói e em que ano ela foi proposta?  
3. Quais são as três regras fundamentais do jogo da Torre de Hanói?  
4. Qual é o objetivo principal do algoritmo da Torre de Hanói?  
5. Qual é a fórmula que calcula o número mínimo de movimentos necessários para resolver o problema com `n` discos?  
6. Quantos movimentos são necessários para resolver o problema com 3 discos?  
7. Qual o tempo de complexidade do algoritmo da Torre de Hanói?  
8. Por que o problema da Torre de Hanói é considerado um exemplo clássico de **recursão**?  
9. O que significa “caso base” em um algoritmo recursivo, e qual é o caso base na Torre de Hanói?  
10. O que acontece com o número de movimentos totais quando se adiciona mais um disco ao problema?

---

## 💻 Parte 2 – Código Java

11. Qual é o papel dos parâmetros `origem`, `destino` e `auxiliar` no método `moverDiscos()`?  
12. O que acontece se o caso base `if (n == 1)` for removido do código?  
13. No trecho abaixo, o que significa a linha `moverDiscos(n - 1, origem, auxiliar, destino);`?

    ```java
    moverDiscos(n - 1, origem, auxiliar, destino);
    System.out.println("Mover disco " + n + " de " + origem + " para " + destino);
    moverDiscos(n - 1, auxiliar, destino, origem);
    ```

14. Por que o algoritmo chama o próprio método dentro dele (recursão)?  
15. O que a função `System.out.println()` exibe em cada iteração da função recursiva?  
16. Como o número de chamadas recursivas está relacionado ao número de discos (`n`)?  
17. O que aconteceria se os parâmetros `destino` e `auxiliar` fossem trocados na primeira chamada recursiva?  
18. Qual é o tipo de dado utilizado para representar as hastes (`A`, `B`, `C`) no código?  
19. No programa com contador de movimentos, qual é a finalidade da variável `contador`?  
20. Se `n = 4`, quantos movimentos o programa imprimirá no total?

---
Resposta

1 R= E um quebra cabeça matematico e logico utilizado para representar e estudar recursividade, planejamento estrategico e resolução de problemas e algoritmos

2 R= Foi criado pelo matemático francês Édoard Lucas em 1883

3 R= So pode mover um disco por vez, nunca colocar um disco maior sobre um menor, a quantidade minima de movimentos e calculada por 2 elevado a N -1

4 R= Mover uma pilha inteira de discos de um pino de origem para um pino de destino, utilizando um pino auxiliar, no numero minimo de movimentos

5 R= 2n -1 onde N e o numero de discos

6 R= 7

7 R= É o exponecial definido como O(2 elevado a n), onde N e o numero de discos

8.  R= Porque o problema é resolvido quebrando-o e subproblemas menores  iguais ao original.
   
9. R= Caso base é quando não há mais divisão possivel
   
10. R= O número de movimentos praticamente dobra +1 . 


