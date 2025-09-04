# LeetCode Solutions in C

Este repositório contém minhas soluções para problemas do [LeetCode](https://leetcode.com/), implementadas em **C**.  
O objetivo é praticar algoritmos e estruturas de dados, documentar o raciocínio e evoluir na análise de complexidade.

---

## 🎯 Objetivos do Repositório
- Resolver problemas do LeetCode de forma consistente.
- Manter código **limpo, comentado e organizado**.
- Documentar a **análise de tempo e espaço** de cada solução.
- Construir um portfólio público que demonstre evolução em programação.

---

## 📂 Estrutura
Os arquivos seguem o padrão:

```
<ID>-<nome-do-problema>.c
```

Exemplo:
  - 0001-two-sum.c
  - 0053-maximum-subarray.c
  - 0344-reverse-string.c


  Cada arquivo contém:
- A função principal da solução.
- Comentários explicando a lógica.
- Análise de complexidade (tempo e espaço).

---

## 🚀 Exemplos

### Problema: [Two Sum](https://leetcode.com/problems/two-sum/)
Arquivo: `0001-two-sum.c`

```c
/**
 * Problema: Dado um array de inteiros, retornar os índices de dois números que somam a um alvo.
 * Estratégia: Hashing para reduzir busca de O(n²) para O(n).
 * Complexidade: Tempo O(n), Espaço O(n).
 */
