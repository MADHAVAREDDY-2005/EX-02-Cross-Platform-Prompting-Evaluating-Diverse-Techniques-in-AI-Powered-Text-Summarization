# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

## Zero-Shot Prompting
### Prompt: "The Basics of Blockchain Technology"
Summarize the following article.
give me in one paragraph
### Chat-GPT:
Blockchain is a decentralized, immutable digital ledger that records transactions securely across multiple participants without intermediaries. While it offers major opportunities such as transparency, efficiency, and security in sectors like finance, supply chain, healthcare, and governance, it faces challenges of scalability, privacy, regulatory uncertainty, and user adoption. Future directions include integration with artificial intelligence, interoperability across different blockchains, and the rise of decentralized finance (DeFi). Recent research highlights novel uses such as hybrid blockchains, social impact applications (e.g., refugee identity, donation tracking), blockchain–IoT integration, data marketplaces, carbon footprint tracking, and decentralized autonomous organizations (DAOs). Overall, blockchain holds vast potential to transform industries, but addressing technical, legal, and environmental hurdles is crucial for realizing a secure, transparent, and sustainable digital future

### Gemini:
Based on the article, blockchain technology is fundamentally a decentralized and distributed ledger system that securely and transparently records transactions across a network of participants. Built on cryptographic principles, it consists of a chain of blocks, with each block containing a set of transactions. These blocks are linked using cryptographic hashes, which ensures that the data is immutable and its integrity is maintained. This decentralized structure eliminates the need for a central authority or intermediary, as transactions are validated and agreed upon through a consensus mechanism among the network's participants.

### Claude:
This research paper examines blockchain technology's fundamentals, challenges, and applications across six domains through experimental studies. Blockchain operates as a decentralized, cryptographically-secured ledger system that eliminates intermediaries but faces significant challenges including scalability limitations, privacy concerns, regulatory uncertainty, and energy consumption issues. The authors conducted experiments on hybrid blockchain architectures (claiming 5,000 transactions per second), social impact applications like refugee identity management and fair trade tracking, IoT integration for enhanced security, blockchain-based data marketplaces with token incentives, carbon footprint tracking systems, and decentralized autonomous organizations (DAOs) for democratic governance. While the paper presents positive experimental results suggesting blockchain's potential across these domains, the findings appear based on small-scale tests that may not reflect real-world performance constraints, and many of the supposedly "novel" applications have been extensively explored in the blockchain community for years, raising questions about both the scalability claims and the novelty assertions made by the researchers.

### Copilot:
The article "The Basics of Blockchain Technology" introduces blockchain as a decentralized, immutable digital ledger system that securely records transactions across a distributed network. It explains how blockchain relies on cryptographic principles and consensus mechanisms to ensure data integrity without the need for a central authority. Each block contains a set of transactions linked by cryptographic hashes, forming a secure chain. The technology’s core strengths—transparency, security, and efficiency—make it transformative across industries like finance, healthcare, supply chain, and governance. Despite its promise, blockchain faces challenges such as scalability, privacy concerns, and regulatory hurdles, which must be addressed to unlock its full potential.
<h2>📊 Evaluation of Zero-Shot Summarization </h2>

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th>Criteria</th>
    <th>ChatGPT</th>
    <th>Gemini</th>
    <th>Claude</th>
    <th>Copilot</th>
  </tr>
  <tr>
    <td><b>Accuracy</b></td>
    <td>⭐⭐⭐⭐½ (High) – covers fundamentals, challenges, future uses clearly</td>
    <td>⭐⭐⭐⭐ (High) – correct fundamentals, but misses opportunities/future directions</td>
    <td>⭐⭐⭐⭐ (High) – technically accurate but over-critical and slightly biased</td>
    <td>⭐⭐⭐⭐ (High) – good fundamentals and applications, less detail on future</td>
  </tr>
  <tr>
    <td><b>Coherence</b></td>
    <td>⭐⭐⭐⭐½ (Very High) – smooth flow and well-organized</td>
    <td>⭐⭐⭐⭐ (High) – structured, but more definitional than summary-like</td>
    <td>⭐⭐⭐⭐ (High) – coherent but dense, more like a critique than summary</td>
    <td>⭐⭐⭐⭐ (High) – flows logically, simple structure</td>
  </tr>
  <tr>
    <td><b>Simplicity</b></td>
    <td>⭐⭐⭐⭐ (High) – clear, but dense with technical terms</td>
    <td>⭐⭐⭐½ (Moderate-High) – easy to follow but more textbook style</td>
    <td>⭐⭐⭐ (Moderate) – academic and critical tone, harder for undergrads</td>
    <td>⭐⭐⭐⭐ (High) – simple, undergraduate-friendly</td>
  </tr>
  <tr>
    <td><b>Speed</b></td>
    <td>⭐⭐⭐⭐⭐ (Fast, ~2s)</td>
    <td>⭐⭐⭐⭐½ (Fast, ~3s)</td>
    <td>⭐⭐⭐⭐ (Moderate, ~4s)</td>
    <td>⭐⭐⭐⭐½ (Fast, ~3s)</td>
  </tr>
  <tr>
    <td><b>User Experience (UX)</b></td>
    <td>⭐⭐⭐⭐½ (Well formatted, neat paragraph)</td>
    <td>⭐⭐⭐⭐ (Neat, but slightly long-winded)</td>
    <td>⭐⭐⭐½ (Dense, critique style, less user-friendly)</td>
    <td>⭐⭐⭐⭐ (Clean and readable)</td>
  </tr>
</table>

<p><b>Final Score (avg):</b><br>
• ChatGPT → 4.4<br>
• Gemini → 4.0<br>
• Claude → 3.8<br>
• Copilot → 4.1
</p>


## 
## Algorithm

## Result


