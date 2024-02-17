## Modelos de prompt para questões discurvisas e de múltipla escolha ##

**Prompt inicial para quesões discursivas**:

\[imagem da questão\]

Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Informe caso a questão não esteja clara ou não tenha resposta possível.

---

**Prompt inicial para quesões de múltipla escolha**:

\[imagem da questão\]

Responda a questão nesta imagem. Explique o seu raciocínio passo a passo. Ao final, escolha qual das cinco alternativas fornecidas (A-E) é a correta. Informe caso haja mais de uma alternativa correta ou todas as cinco alternativas sejam incorretas.

---

**Prompt de reavaliação para questões discursivas (no caso da resposta do modelo diferir do padrão de resposta da questão)**:

As suas respostas não estão completamente consistentes em relação ao padrão de resposta divulgado para esta questão:

\[padrão de resposta\]

Após analisar o padrão de resposta, você mantém ou altera as respostas originais? Se decidir alterar suas respostas, explique as possíveis razões que o induziram aos erros nas respostas anteriores. Procure identificar as causas concretas dos erros, ao invés de listar razões genéricas como falha de compreensão do enunciado da questão.

---

**Prompt de reavaliação para questões de múltipla escolha (no caso da resposta do modelo diferir do gabarito)**:

A sua resposta difere do gabarito divulgado para esta questão: 

\[gabarito\]

Após analisar o gabarito, você mantém ou altera sua resposta? Se decidir alterar sua resposta, explique as possíveis razões que o induziram ao erro. Procure identificar as causas concretas do seu erro, ao invés de listar razões genéricas como falha de compreensão do enunciado da questão.

---

**Prompt para análise pelo ChatGPT-4 Turbo (para questões discursivas e de múltipla escolha com repostas iniciais discordantes)**:

\[imagem da questão\]

Seguem os prompts e as respostas de uma IA gerativa para a questão em anexo, juntamente com possíveis avaliações de dois ou mais especialistas humanos sobre as respostas da IA generativa e a qualidade geral da questão. Com base nas informações fornecidas, resuma as principais dificuldades enfrentadas pela IA gerativa ao tentar responder à questão, incluindo possíveis dificuldades resultantes do reconhecimento incorreto de algum elemento gráfico ou textual presente no enunciado da questão. Considere apenas dificuldades concretas cuja manifestação pode ser evidenciada pelas informações fornecidas nas respostas da IA gerativa. Ao final, discuta se essas dificuldades poderiam ser mitigadas ou eliminadas por meio de técnicas de engenharia de prompts ou se seriam inerentes às limitações dos atuais grandes modelos de linguagem de grande (LLMs).

\[Prompts e respostas do ChatGPT-4 Vision\]

\[avaliações dos especialistas (quando disponíveis)\] 
