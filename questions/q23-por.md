\[ [Questão anterior](q22-por.md) \] \[ [Próxima questão](q24-por.md) \] \[ [Menu inicial](/README.md) \] \[ [Versão em Inglês](q23-eng.md) \] 

## Questão 23 ##

<img src="q23-image.png" alt="Question 23 image file" width="60%" height="60%">

**Prompt**: Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Ao final, escolha qual das cinco alternativas fornecidas (A-E) é a correta. Informe caso haja mais de uma alternativa correta ou todas as cinco alternativas sejam incorretas.

---

**Resposta do ChatGPT-4 Vision**: 

Vamos resolver a questão passo a passo:

### Árvore Binária de Busca:
Conforme descrito, numa árvore binária de busca, o filho à esquerda de um nó tem valor numericamente menor do que o nó, e o filho à direita tem valor numericamente maior ou igual ao nó.

Dada a lista de elementos: 27, 34, 40, 18, 23, 5, 25, 36, 10, 7, -2

A inserção na árvore acontecerá na ordem da lista:

1. **27** - Será a raiz da árvore.
2. **34** - Maior que 27, logo, vai para a direita de 27.
3. **40** - Maior que 27 e 34, logo, vai para a direita de 34.
4. **18** - Menor que 27, logo, vai para a esquerda de 27.
5. **23** - Maior que 18 mas menor que 27, logo, vai para a direita de 18.
6. **5** - Menor que 27 e 18, logo, vai para a esquerda de 18.
7. **25** - Maior que 18 e 5 mas menor que 23 e 27, logo, vai para a esquerda de 23.
8. **36** - Maior que 27 e 34 mas menor que 40, logo, vai para a esquerda de 40.
9. **10** - Menor que 27 e 18 mas maior que 5, logo, vai para a direita de 5.
10. **7** - Menor que 27, 18 e 10 mas maior que 5, logo, vai para a esquerda de 10.
11. **-2** - Menor que todos, logo, vai para a esquerda de 5.

### Análise das alternativas:

**A.** A árvore resultante tem **4 níveis de altura** (contando com a raiz), com 4 elementos à esquerda da raiz principal (inicial) e 3 à direita.

**B.** Percorrendo em Pré-ordem:
- Processamos a raiz, depois a subárvore da esquerda, e finalmente a subárvore da direita.
- Ordem: 27, 18, 5, -2, 10, 7, 23, 25, 34, 40, 36.

**C.** Percorrendo em Em-ordem:
- Processamos a subárvore da esquerda, depois a raiz, e finalmente a subárvore da direita.
- Ordem: -2, 5, 7, 10, 18, 23, 25, 27, 34, 36, 40.

**D.** Percorrendo em Pós-ordem:
- Processamos a subárvore da esquerda, depois a subárvore da direita, e finalmente a raiz.
- Ordem: -2, 7, 10, 5, 25, 23, 18, 36, 40, 34, 27.

**E.** O número máximo de elementos que uma árvore binária pode ter com 10 níveis é \(2^{10} - 1\), que é 1023.

Portanto, a alternativa correta é **C**.

---

**Gabarito**: C

---

**Veredito**

A resposta do ChatGPT é consistente com o gabarito.

\[ [Questão anterior](q22-por.md) \] \[ [Próxima questão](q24-por.md) \] \[ [Menu inicial](/README.md) \]
