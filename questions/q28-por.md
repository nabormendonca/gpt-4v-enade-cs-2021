\[ [Questão anterior](q27-por.md) \] \[ [Próxima questão](q29-por.md) \] \[ [Menu inicial](/README.md) \] \[ [Versão em Inglês](q28-eng.md) \] 

## Questão 28 ##

<img src="q28-image.png" alt="Question 28 image file" width="60%" height="60%">

**Prompt**: Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Ao final, escolha qual das cinco alternativas fornecidas (A-E) é a correta. Informe caso haja mais de uma alternativa correta ou todas as cinco alternativas sejam incorretas.

---

**Resposta do ChatGPT-4 Vision**: 

Vamos começar analisando cada uma das afirmações:

I. **Uma falta na busca de instrução (nenhuma instrução buscada), em determinado ciclo, causará uma bolha (ausência de instrução útil) no estágio S1, e essa bolha percorrerá todos os estágios seguintes, um após o outro, nos próximos 4 ciclos, até ser eliminada do pipeline.**
   - Isso é verdade. Se observarmos o modelo de pipeline fornecido, podemos perceber que uma falta no estágio de busca de instrução (S1) fará com que essa falta (ou bolha) passe por todos os estágios subsequentes, tomando um ciclo em cada estágio. Como temos 5 estágios, levará 4 ciclos adicionais (além do ciclo no qual a falta ocorreu) para que a bolha seja eliminada.

II. **Cada instrução leva 5 ciclos para ser executada, mas se alguma instrução não precisar passar por determinado estágio, ela poderá percorrer o pipeline em um número menor de ciclos, por exemplo, se a instrução não possuir operandos ela não precisará passar pelo estágio S3 e assim poderá ser movida diretamente para o estágio S4.**
   - Isso é impreciso. Mesmo se uma instrução não precisar de operandos, ela ainda ocupará um slot no estágio S3 e simplesmente não realizará nenhuma operação durante esse estágio. O pipeline é projetado para permitir o processamento simultâneo de várias instruções em diferentes estágios, mas cada instrução ainda passa por cada estágio em sequência. Portanto, essa afirmação é **falsa**.

III. **Dispondo de cache de dados separada da cache de instruções, o estágio S1 busca instruções na cache de instruções e dados na cache de dados.**
   - Isso é verdade. Em sistemas que possuem caches separadas para instruções e dados (arquiteturas com cache Harvard), a busca de instruções ocorrerá na cache de instruções e a busca de dados (por exemplo, operandos) ocorrerá na cache de dados.

IV. **Dispondo de BTB (branch target buffer), após a busca de uma instrução de desvio condicional, as instruções seguintes podem ser buscadas e colocadas no pipeline, o que evita bolhas em seus vários estágios.**
   - Isso é verdade. O BTB é uma estrutura de hardware usada para prever o resultado de instruções de desvio condicional. Se um desvio é previsto como tomado, o BTB pode fornecer o endereço alvo do desvio, permitindo que a próxima instrução seja buscada sem esperar que o desvio atual seja resolvido, ajudando assim a evitar bolhas no pipeline.

Analisando as opções:

A) I e II. 
B) I e IV. 
C) II e IV. 
D) I, II e III. 
E) II, III e IV.

A opção correta é a alternativa **B) I e IV**, pois ambas as afirmações I e IV são verdadeiras.

---

**Gabarito**: B

---

**Veredito**

A resposta do ChatGPT é consistente com o gabarito.

\[ [Questão anterior](q27-por.md) \] \[ [Próxima questão](q29-por.md) \] \[ [Menu inicial](/README.md) \] \[ [Versão em Inglês](q28-eng.md) \] 
