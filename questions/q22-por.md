\[ [Questão anterior](q21-por.md) \] \[ [Próxima questão](q23-por.md) \]

## Questão 22 ##

<img src="q22-image.png" alt="Question 22 image file" width="75%" height="75%">

**Prompt**: Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Ao final, escolha qual das cinco alternativas fornecidas (A-E) é a correta. Informe caso haja mais de uma alternativa correta ou todas as cinco alternativas sejam incorretas.

---

**Resposta do ChatGPT-4 Vision**: 

Vamos começar pela análise do Diagrama Entidade Relacionamento (DER) apresentado e entender cada uma das entidades e suas relações:

1. **TIPO_PET**: Representa o tipo de animal, com os atributos código e descrição.
2. **PESSOA**: Representa uma pessoa, com os atributos cpf e nome. 
3. **PET**: Representa um animal amparado pela ONG, com os atributos nome, data_nascimento, código e possui relações com TIPO_PET e PESSOA.

Relações observadas:
1. Cada PET pertence a um tipo, indicado pela relação "pertencer" entre PET e TIPO_PET.
2. Cada PET pode ser adotado por uma PESSOA, conforme a relação "adotar" entre PET e PESSOA.

Com base nisso, vamos analisar as alternativas:

**A)**
- PESSOA(cpf: texto, nome: texto): Parece correto.
- TIPO_PET(codigo: inteiro, descricao: texto): Parece correto.
- PET(codigo: inteiro, nome: texto, data_nascimento: data, codigo_tipo_pet: inteiro, adotante: texto): Parece correto, já que tem uma referência ao TIPO_PET pelo código e uma referência à PESSOA pelo CPF (adotante).

**B)**
- PET(codigo: inteiro, nome: texto, data_nascimento: data): Parece correto.
- PESSOA(cpf: texto, nome: texto, codigo_pet: inteiro): Isto sugere que uma pessoa pode adotar apenas um pet, o que contraria o DER que permite que uma pessoa adote múltiplos pets (0,n).
- TIPO_PET(codigo: inteiro, descricao: texto, codigo_pet: inteiro): Isso sugere que um tipo de animal está ligado a um único pet, o que não é verdade.

**C)**
- TIPO_PET(codigo: inteiro, descricao: texto): Parece correto.
- PET(codigo: inteiro, nome: texto, data_nascimento: data, codigo_tipo_pet: inteiro): Parece correto.
- PESSOA(cpf: texto, nome: texto, codigo_pet: inteiro): Novamente, sugere que uma pessoa só pode adotar um pet.

**D)**
- PET_PESSOA(codigo_pet: inteiro, nome_pet: texto, data_nascimento: data, cpf: texto, nome_pessoa: texto, codigo_tipo_pet: inteiro, descricao_tipo_pet: texto): Parece uma junção de todas as entidades em uma única tabela, o que não é o modelo relacional apropriado.

**E)**
- PESSOA(cpf: texto, nome: texto): Parece correto.
- PET(codigo: inteiro, nome: texto, data_nascimento: data, codigo_tipo_pet: inteiro, descricao_tipo_pet, adotante: texto): Aqui, estamos incluindo o "descricao_tipo_pet" diretamente na tabela PET, o que é uma redundância desnecessária e não é uma prática apropriada.

A alternativa mais adequada que traduz corretamente o DER para o esquema relacional é a **Alternativa A**.

---

**Gabarito**: A

---

**Veredito**

A resposta do ChatGPT é consistente com o gabarito.

\[ [Questão anterior](q21-por.md) \] \[ [Próxima questão](q23-por.md) \]
