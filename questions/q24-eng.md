## Question 24 ##

(Click [here](q24-image.png) to view the question in its original image format in Portuguese)

WhatsApp's end-to-end encryption ensures that only you and the person with whom you're communicating can read what is sent. Nobody else will have access to it, not even WhatsApp. Your messages are secured with locks and only you and the recipient have the special keys needed to unlock and read your messages. And for even greater protection, each message you send comes with its own unique lock and key.

Available at: https://faq.whatsapp.com/pt_br/general/28030015. Accessed on: May 5, 2020.

Based on the text above and considering the concepts of security and cryptography, evaluate the following statements.

I. If a pair of keys is generated during the app installation and the user's public key is stored on the server, it is possible to verify the authenticity of a received message using the sender's public key obtained from the server.

II. The strategy of using a variable initialization vector (IV) for composing different cryptographic keys for each message sent hides data patterns, as well as making so-called replay attacks more difficult.

III. The use of the AES algorithm in communications between two users indicates the use of symmetric cryptography, that is, one that uses a pair of keys, one used by the sender to encrypt a message, and another by the recipient to decrypt it.

IV. The presence of the SHA-256 algorithm in the client-server communication protocol suggests the integrity verification of the messages, since it is possible to detect any alterations by comparing the hash values of the sent and received message.

It is correct only what is stated in

A) I and IV.

B) II and III.

C) III and IV.

D) I, II and III.

E) I, II and IV.**Prompt**: Please answer the question(s) in this image by explaining step by step the reasoning used to answer it (them). At the end, choose which of the five provided alternatives (A-E) is the correct one. Inform if there is more than one correct alternative or if all five alternatives are incorrect.

**ChatGPT-4 Vision response**: 

Let's evaluate each statement separately, based on the concepts of security and cryptography:

I. If a key pair is generated during the app installation and the user's public key is stored on the server, it's possible to verify the authenticity of a received message using the sender's public key obtained from the server.

- **Correct**. In asymmetric cryptography, the public key is used to verify the digital signature made with the sender's private key, thus ensuring authenticity.

II. The strategy of using a variable Initialization Vector (IV) to compose different cryptographic keys for each message sent hides data patterns, as well as making the so-called replay attacks harder.

- **Correct**. The IV is used to ensure that the same message isn't encrypted the same way every time. It adds randomness to the encryption process and is a standard practice in many encryption schemes to prevent exposing patterns and resist replay attacks.

III. The use of the AES algorithm in communications between two users indicates the employment of symmetric encryption, that is, the one that uses a pair of keys, one used by the sender to encrypt the message, and another for the recipient to decrypt it.

- **Partially Correct**. AES is a symmetric encryption algorithm, which means that the same key is used for both encrypting and decrypting the message. However, the phrase is a bit misleading when saying "a pair of keys". In symmetric encryption, it's a single shared key, not a pair of distinct keys.

IV. The presence of the SHA-256 algorithm in the client-server communication protocol suggests checking the integrity of messages, since it is possible to detect if any modification occurred by comparing the hash values of the sent and received message.

- **Correct**. SHA-256 is a cryptographic hash function. Its purpose is to verify data integrity. By creating a hash of a message and comparing that hash on the receiver's side, it can be checked if the message was altered during transmission.

Given the above, statements I, II, and IV are correct, while statement III is partially correct.

Therefore, the correct alternative is **E, I, II and IV**.

---

**Answer Key**: E

---

**Verdict**

The ChatGPT's answer is consistent with the answer key.
