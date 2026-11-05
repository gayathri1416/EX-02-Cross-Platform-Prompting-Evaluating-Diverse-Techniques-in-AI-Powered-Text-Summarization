# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
1. Prepare a 500-word article on "The Basics of Blockchain Technology".
2. Select five prompt structures: Basic, Role, Context, Constraint and Output Format.
3. Apply these five prompt structures to the article using an AI platform and collect the generated summaries.
4. Select three AI platforms: ChatGPT, Claude and Microsoft Copilot.
5. Choose four prompting techniques: Zero-Shot, Few-Shot, Chain-of-Thought and Role-Based Prompting.
6. Provide the same article and corresponding prompts to all three AI platforms.
7. Collect the generated outputs and record their response times.
8. Evaluate the AI-generated summaries based on Accuracy, Coherence, Simplicity, Speed and User Experience.
9. Compare the results, calculate average scores and identify the most efficient AI platform and prompting technique.
# DIFFERENT PROMPT STRUCTURES
Application: Text Summarization

Input Topic: The Basics of Blockchain Technology

The Basics of Blockchain Technology

Blockchain is a modern digital technology used to store and manage information securely across a network of computers. It is a type of distributed digital ledger that records transactions in a transparent and organized manner. Unlike traditional databases, where information is usually controlled by a single organization or authority, blockchain allows multiple participants to maintain and verify the same records. This makes the technology more transparent, reliable, and difficult to manipulate.

The word blockchain comes from two terms: "block" and "chain." A block is a collection of digital information containing transaction details, a timestamp, and a unique identification code called a hash. Each block is connected to the previous block using its hash, forming a continuous chain of records. This connection helps protect the information because changing data in one block can affect the links between the following blocks.

Blockchain works through a network of computers called nodes. When a person initiates a transaction, the information is shared with the network. The participating computers verify the transaction using agreed rules known as consensus mechanisms. Once the transaction is verified, it is grouped with other transactions into a new block. The block is then added to the existing blockchain, and the updated information is shared across the network. This process ensures that participants have access to consistent records.

One of the important features of blockchain is decentralization. In a decentralized system, no single central authority has complete control over the entire network. Instead, multiple computers participate in maintaining the records. Another important feature is transparency, as participants with the required access can view recorded transactions. Blockchain also provides security through cryptographic techniques, which help protect data from unauthorized changes. Once information is added and confirmed, modifying it becomes extremely difficult.

Blockchain technology is widely known for its role in cryptocurrencies such as Bitcoin and Ethereum. However, its applications are not limited to digital currencies. It can also be used in supply chain management to track products from manufacturers to customers. In healthcare, blockchain can help maintain secure medical records. In banking, it can support faster and more transparent financial transactions. It is also useful in digital identity management, voting systems, and smart contracts. Smart contracts are programs stored on a blockchain that automatically execute predefined actions when specific conditions are met.

Despite its advantages, blockchain has some limitations. Certain blockchain networks require significant computing power and energy. Transaction processing can sometimes be slower compared to traditional systems. Implementation costs, technical complexity, and regulatory challenges can also create difficulties for organizations adopting this technology.

In conclusion, blockchain is an innovative technology that provides a secure, transparent, and decentralized way to record and share information. Although it has certain limitations, it has the potential to improve how data and transactions are managed across various industries. Understanding its basic concepts helps students recognize its importance in the development of modern digital systems.

# 1. BASIC PROMPT
# Prompt:
Summarize the given article about "The Basics of Blockchain Technology" in simple words.

# Output:

Blockchain is a digital technology used to store and manage information securely across a network of computers. It records transactions in blocks that are connected using unique identification codes called hashes. Multiple computers verify transactions before adding them to the blockchain. Its main features include decentralization, transparency, and security. Blockchain is widely used in cryptocurrencies such as Bitcoin and Ethereum, as well as healthcare, banking, supply chain management, and digital identity systems. Although it offers several advantages, it also has limitations such as high energy consumption, slower transaction processing, and implementation costs.

# 2. ROLE PROMPT
# Prompt:
Act as an experienced computer science teacher. Summarize the given article about "The Basics of Blockchain Technology" in a way that is easy for undergraduate students to understand.

# Output:

Blockchain is a technology that helps store information securely across multiple computers instead of depending on one central authority. It works by storing transaction details in groups called blocks, which are connected together to form a chain. Each block contains information and a unique code called a hash.

When a transaction takes place, computers in the network verify it before adding it to the blockchain. This makes the information more secure and difficult to change.

The important features of blockchain are decentralization, transparency, and security. It is commonly used in cryptocurrencies like Bitcoin and Ethereum. Other applications include banking, healthcare, supply chain management, and digital identity systems.

However, blockchain also has some disadvantages, such as high energy consumption, processing delays, and implementation costs. Overall, blockchain is an important technology that helps manage digital information securely and transparently.

# 3. CONTEXT PROMPT
# Prompt:
I am a second-year undergraduate computer science student learning about emerging technologies. I need to understand the basic concepts of blockchain technology for my academic studies. Summarize the given article by highlighting its working process, important features, applications, advantages, and limitations.

# Output:

Blockchain is a distributed digital ledger technology that stores information securely across a network of computers. Instead of depending on a single central authority, multiple computers maintain and verify the records.

Working Process:
- Transactions are shared with computers in the network.
- The computers verify the transactions using agreed rules.
- Verified transactions are grouped into blocks.
- Each block is connected to the previous block using a unique hash.
- The updated blockchain is shared across the network.
Important Features:
- Decentralization: No single authority controls the entire network.
- Transparency: Participants can view recorded transactions according to their access.
- Security: Cryptographic techniques protect information from unauthorized changes.
Applications:
Blockchain is used in cryptocurrencies, banking, healthcare, supply chain management, digital identity systems, and smart contracts.

Limitations:
Some blockchain networks consume high energy, process transactions slowly, and involve technical complexity and implementation costs.

Blockchain is an important technology that provides a secure and transparent method of managing digital information across different industries.

# 4. CONSTRAINT PROMPT
# Prompt:
Summarize the given article about "The Basics of Blockchain Technology" by following these conditions:

 Keep the summary between 100 and 120 words.
 Use simple English.
 Include the working process, main features, applications, and limitations.
 Avoid unnecessary technical explanations.
 Do not introduce information that is not present in the article.
# Output:

Blockchain is a digital technology that stores information securely across multiple computers. It records transactions in blocks connected using unique codes called hashes. Computers in the network verify transactions before adding them to the blockchain. Its main features are decentralization, transparency, and security. Blockchain is widely used in cryptocurrencies such as Bitcoin and Ethereum. It also supports applications in banking, healthcare, supply chain management, digital identity, and smart contracts. Despite its benefits, blockchain has limitations such as high energy consumption, slower transaction processing, technical complexity, and implementation costs. Overall, blockchain provides a secure and transparent way to manage digital information across various industries.

# 5. OUTPUT FORMAT PROMPT
# Prompt:
Summarize the given article about "The Basics of Blockchain Technology" using the following output format:

1. Introduction – Briefly explain blockchain.
2. Working Process – Explain how blockchain works.
3. Key Features – List its important features.
4. Applications – Mention its major applications.
5. Limitations – Explain its disadvantages.
6. Conclusion – Give a short overall summary.

Use simple English and clear bullet points. Keep the explanation suitable for undergraduate students.

# Output:

1. Introduction:

Blockchain is a distributed digital ledger technology that stores information securely across multiple computers without depending on a single central authority.

2. Working Process:
- Transactions are shared with the network.
- Computers verify the transactions.
- Verified transactions are grouped into blocks.
- Each block is connected to the previous block using a unique hash.
- The updated blockchain is shared with the network.
3. Key Features:
- Decentralization: No single authority controls the entire network.
- Transparency: Participants can access recorded transactions according to their permissions.
- Security: Cryptographic techniques protect information from unauthorized changes.
4. Applications:
- Cryptocurrencies such as Bitcoin and Ethereum.
- Healthcare record management.
- Banking and financial transactions.
- Supply chain product tracking.
- Digital identity management.
- Smart contracts.
5. Limitations:
- High energy consumption in certain networks.
- Slower transaction processing.
- Technical complexity.
- Implementation costs.
- Regulatory challenges.

6. Conclusion:

Blockchain is an innovative technology that provides a secure, transparent, and decentralized method of storing and sharing information. It has several applications across different industries, although certain technical and operational limitations still exist.

# Cross-Platform-Prompting-Evaluating
### Table 1: Prompt Details and AI Tools Used

| S.No | Prompt Title               | Prompt Given                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | AI Tools Used                      |
| ---- | -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| 1    | Zero-Shot Prompting        | Summarize the article "The Basics of Blockchain Technology" in simple and clear English. Identify the main ideas, including its definition, working process, key features, applications, and limitations. Keep the summary concise and suitable for undergraduate students.                                                                                                                                                                                                                                                               | ChatGPT, Claude, Microsoft Copilot |
| 2    | Few-Shot Prompting         | You are an AI assistant specialized in creating short educational summaries. Study the following examples and follow the same summarization style. Example 1: Cybersecurity protects computers, networks, and data from unauthorized access and cyberattacks. Example 2: IoT connects physical devices to the internet to collect and exchange data. Now summarize the blockchain article in a similar style, including its definition, working process, features, applications, and limitations. Use simple English and keep it concise. | ChatGPT, Claude, Microsoft Copilot |
| 3    | Chain-of-Thought Prompting | Analyze the given article "The Basics of Blockchain Technology" step by step. Identify its main concepts, working process, key features, applications, and limitations. Organize the important points logically and prepare a clear, accurate, and concise summary in simple English suitable for undergraduate students. Avoid unnecessary technical details.                                                                                                                                                                            | ChatGPT, Claude, Microsoft Copilot |
| 4    | Role-Based Prompting       | Act as an experienced computer science professor. Summarize the previously provided article "The Basics of Blockchain Technology" for undergraduate students. Explain the important concepts, working process, key features, applications, and limitations using simple English. Make the summary clear, informative, and easy to understand.                                                                                                                                                                                             | ChatGPT, Claude, Microsoft Copilot |

### Table 2: Detailed AI Evaluation Scores

| S.No | Prompt Title     | AI Tool | Accuracy | Coherence | Simplicity | Speed     | User Experience |
| ---- | ---------------- | ------- | -------- | --------- | ---------- | --------- | --------------- |
| 1    | Zero-Shot        | ChatGPT | 9        | 9         | 9.5        | Same time | 9               |
| 2    | Zero-Shot        | Claude  | 9.5      | 9.5       | 9          | Same time | 9.5             |
| 3    | Zero-Shot        | Copilot | 9.5      | 9.5       | 9          | Same time | 9.5             |
| 4    | Few-Shot         | ChatGPT | 9.5      | 9.5       | 9.5        | Same time | 9.5             |
| 5    | Few-Shot         | Claude  | 9.5      | 9.5       | 9          | Same time | 9.5             |
| 6    | Few-Shot         | Copilot | 9        | 9         | 10         | Same time | 9               |
| 7    | Chain-of-Thought | ChatGPT | 9.5      | 9.5       | 9.5        | 1st       | 9.5             |
| 8    | Chain-of-Thought | Claude  | 10       | 10        | 9          | 3rd       | 9.5             |
| 9    | Chain-of-Thought | Copilot | 9.5      | 9.5       | 9.5        | 2nd       | 9.5             |
| 10   | Role-Based       | ChatGPT | 9.5      | 9.5       | 9.5        | 1st       | 9.5             |
| 11   | Role-Based       | Claude  | 10       | 10        | 9.5        | 3rd       | 10              |
| 12   | Role-Based       | Copilot | 9.5      | 9.5       | 9.5        | 2nd       | 9.5             |

### Table 3: Overall AI Evaluation

| AI Tool           | Accuracy | Coherence | Simplicity | Speed | User Experience |
| ----------------- | -------- | --------- | ---------- | ----- | --------------- |
| ChatGPT           | 9.4      | 9.4       | 9.5        | 1st   | 9.4             |
| Claude            | 9.6      | 9.8       | 9.1        | 3rd   | 9.6             |
| Microsoft Copilot | 9.4      | 9.4       | 9.5        | 2nd   | 9.4             |

Scores are approximate averages across all four prompting techniques.
## Result

The experiment was successfully conducted in two stages. In the first stage, five different prompt structures (Basic, Role, Context, Constraint and Output Format) were tested using a 500-word blockchain article to observe how prompt instructions influence the generated summaries.

In the second stage, four prompting techniques (Zero-Shot, Few-Shot, Chain-of-Thought and Role-Based) were tested across ChatGPT, Claude and Microsoft Copilot, producing 12 AI-generated outputs.

Overall, the experiment demonstrated how different prompt structures and prompting techniques influence AI-generated text summarization and helped compare the efficiency of different AI platforms.
