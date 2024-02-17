\[ [Questão anterior](q15-por.md) \] \[ [Próxima questão](q17-por.md) \] \[ [Menu inicial](/README.md) \] \[ [Versão em Inglês](q16-eng.md) \] 

## Questão 16 ##

<img src="q16-image.png" alt="Question 16 image file" width="60%" height="60%">

**Prompt**: Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Ao final, escolha qual das cinco alternativas fornecidas (A-E) é a correta. Informe caso haja mais de uma alternativa correta ou todas as cinco alternativas sejam incorretas.

---

**Resposta do ChatGPT-4 Vision**: 

Vamos analisar o circuito combinacional apresentado e determinar a expressão booleana correspondente, passo a passo.

1. **Primeiros dois NOT Gates**:
   - X1 passa por um gate NOT. Portanto, a saída dessa porta é X1' (negado).
   - X2 também passa por um gate NOT. A saída é X2' (negado).

2. **Porta AND**:
   - Temos duas entradas para essa porta: X3 e a saída do gate NOT de X2, que é X2'.
   - A expressão para a porta AND é multiplicação em álgebra booleana. Portanto, a saída desse gate é X3 . X2' ou X3 AND X2'.

3. **Porta OR**:
   - As entradas para essa porta são a saída da porta AND e a saída do gate NOT de X1, que é X1'.
   - A expressão para a porta OR é adição em álgebra booleana. Portanto, a saída deste gate é (X3 . X2') + X1' ou (X3 AND X2') OR X1'.

4. **Último NOT Gate**:
   - A saída da porta OR passa pelo último gate NOT.
   - Portanto, a expressão final é negar toda a expressão anterior: [(X3 . X2') + X1']'

Juntando tudo, obtemos a expressão booleana: **[(X3 . X2') + X1']'**

Agora, vamos comparar isso com as opções fornecidas:

A) (X3 . X2') + X1'
B) (X3 . (X2') + (X1'))'
C) (X3 . X2') + X1'
D) (X3 . X2') + X1'
E) (X3 . X2')' + X1'

A expressão que determinamos é a **opção B**, que é: (X3 . (X2') + (X1'))'

---

**Gabarito**: B

---

**Veredito**

A resposta do ChatGPT é consistente com o gabarito.

\[ [Questão anterior](q15-por.md) \] \[ [Próxima questão](q17-por.md) \] \[ [Menu inicial](/README.md) \]
