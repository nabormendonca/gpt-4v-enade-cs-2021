## Prompt templates for open and multiple-choice questions ##

**Initial prompt for open questions**:

\[attached question image\]

Answer the question in this image. Explain your reasoning step by step. Inform if the question is unclear or has no possible answer.

---

**Initial prompt for multiple-choice questions**:

\[attached question image\]

Answer the question in this image. Explain your reasoning step by step. At the end, choose which of the five alternatives (A-E) is correct. Inform if there is more than one correct alternative or if all five alternatives are incorrect.

---

**Reassessment prompt for open questions (in case the model's response disagrees with the question's response standard)**:

Your response is not entirely consistent with the response standard released for this question:

\[response standard\]

After analyzing the response standard, do you maintain or change your original response? If you decide to change your response, explain the possible reasons that led you to errors in the previous response. Try to identify the concrete causes of the errors instead of listing generic reasons, such as a failure to understand the question statement.

---

**Reassessment prompt for multiple-choice questions (in case the model's response disagrees with the question's answer key)**:

Your response differs from the answer key released for this question: 

\[answer key\]

After analyzing the answer key, do you maintain or change your response? If you decide to change your response, explain the possible reasons that led you to errors in the previous answer. Try to identify the concrete causes of the errors instead of listing generic reasons, such as a failure to understand the question statement.

---

**ChatGPT-4 Turbo analysis prompt (for open and multiple-choice questions with initial disagreeing responses)**:

\[attached question image\]

The following are the prompts and responses of a generative AI for the attached question, along with possible assessments by two or more human experts on the generative AI's responses and the general quality of the question. Based on the provided information, summarize the main difficulties faced by the generative AI in attempting to answer the question, including possible difficulties resulting from incorrect recognition of some graphical or textual element present in the statement of the question. Consider only concrete difficulties whose manifestation can be evidenced by the information provided in generative AI's responses. At the end, discuss if these difficulties could be mitigated or eliminated by using prompt engineering techniques or if they would be inherent to the limitations of current large language models (LLMs).\\

\[ChatGPT-4 Vision's prompts and responses\]

\[expert assessments (when available)\] 
