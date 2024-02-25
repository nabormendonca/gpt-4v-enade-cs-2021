\[ [Previous question](q10-eng.md) \] \[ [Next question](q12-eng.md) \] \[ [Main menu](/README.md) \] \[ [Portuguese version](q11-por.md) \] 

## Question 11 ##

<img src="q11-image.png" alt="Question 11 image file" width="60%" height="60%">

**English transcription of the question:**

A team of computer scientists from a certain animation company has been tasked with developing a system capable of scanning the web to detect sites that might be using the company's animation character images without proper consent. Therefore, the system should receive images as input, and classify them between company images and images not produced by the company.

The figure below outlines a deep neural network architecture and the training process the scientists intend to use.

\[The image shows a flow diagram for a deep neural network architecture, consisting of an input layer (Entrada (X)), a series of intermediary layers (Pesos 1, ..., Pesos n, with Camada de Entrada, ..., and Camada Intermediária n between the weight layers), leading to an output layer (Camada de Saída). This is followed by Predicted Outputs (Saídas Previstas (Y')) being compared with Real Outputs (Saídas Reais (Y)) using a Loss Function (Função de Perda), which feeds into an Optimizer (Otimizador) that adjusts the weights (Ajuste dos pesos).\]

CHOULLET, F. Deep Learning with Python. New York: Manning Publications, 2017 (adapted).

After one attempt, two difficulties were noticed: 1) the network training time was too long, and 2) the network's accuracy was not at an acceptable level for the company.

Given these findings, consider the following statements.

I.    Increasing the number of layers is an alternative that can lead to an improvement in accuracy, as well as decreasing the network training time.

II.   Making use of convolutional networks is an alternative that can lead to an improvement in accuracy, however, it may require the use of machines with greater processing power.

III.  Increasing the number of processing units (neurons) in the layers may lead to an improvement in accuracy, as well as decreasing the network training time.

IV.   Increasing the number of training samples is an alternative that can lead to an improvement in accuracy, as well as decreasing the network training time.

V.    Making use of recurrent networks is an alternative that can lead to an improvement in accuracy, however, it may require the use of machines with greater processing power.

It is correct only what is stated in

A) I and IV.

B) I and V.

C) II and III.

D) II and IV.

E) III and V.

---

**Prompt**: Answer the question in this image. Explain your reasoning step by step. At the end, choose which of the five alternatives (A-E) is correct. Inform if there is more than one correct alternative or if all five alternatives are incorrect.

---

**ChatGPT-4 Vision response**:

Let’s analyze the statements:

I. **Increasing the number of layers is an alternative that can lead to an improvement in accuracy, as well as decrease the training time of the network.**
   - This is partially correct. Increasing the number of layers can improve accuracy, as it makes the network deeper and able to capture more complex features. However, it generally does not decrease training time, in fact, it may increase it since there are more parameters to be adjusted.

II. **Making use of convolutional networks is an alternative that can lead to an improvement in accuracy, however, it may require the use of machines with greater processing power.**
   - This is true. Convolutional Neural Networks (CNNs) are widely used for image-related tasks and generally perform better on such tasks compared to fully connected networks. However, due to their nature and the number of operations involved, they may require more computing power, especially for large data volumes.

III. **Increasing the number of processing units (neurons) in the layers can lead to an improvement in accuracy, as well as decrease the training time of the network.**
   - Increasing the number of neurons can improve accuracy since it allows the network to capture more features. However, similar to the first statement, increasing the number of neurons will likely not decrease the training time; in fact, it might increase it because there are more parameters to be trained.

IV. **Increasing the number of training samples is an alternative that can lead to an improvement in accuracy, as well as increase the training time of the network.**
   - This is true. More data generally lead to more robust and accurate models. However, with more data, the training time will increase because there are more examples for the network to process.

V. **Making use of recurrent networks is an alternative that can lead to an improvement in accuracy, however, it may require the use of machines with greater processing power.**
   - Recurrent Neural Networks (RNNs) are commonly used for sequences or temporal data. They are not typically the first choice for image classification tasks. Therefore, this statement is potentially misleading in the context of this question.

Given the above analyses, statements **II and IV** are the most accurate.

Answer: D) II and IV.

---

**Answer key**: D

---

**Verdict**

The response from ChatGPT is consistent with the answer key.


\[ [Previous question](q10-eng.md) \] \[ [Next question](q12-eng.md) \] \[ [Main menu](/README.md) \] \[ [Portuguese version](q11-por.md) \] 
