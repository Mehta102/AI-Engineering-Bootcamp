Section 6: Challenges in Generative AI

1. Introduction
Generative AI tools like ChatGPT have revolutionized content creation, but it's essential to engage with them critically. These tools are powerful, yet not flawless.

2. Hallucinations
Hallucinations occur when AI outputs false or misleading information.
- Causes: Often due to incorrect training data or model limitations.
- Mitigation Strategy: Encourage users to prompt the AI explicitly to respond only when confident.

3. Inconsistencies
AI can produce different answers to the same question.
- This was common in the early versions of ChatGPT.
- Tip: Giving the AI more time to respond can lead to more consistent and thoughtful outputs.

4. Conclusion
Understanding and addressing issues like hallucinations and inconsistencies is crucial. These efforts are vital for the ongoing advancement of generative AI.

---

AI Model Performance: Key Factors

Two Main Determinants

Dataset Size and Quality
- The data acts like a library — the richer and more extensive it is, the better the AI can learn.

Model Size (Parameters)
- The model functions like a student — more parameters equate to better memory and reasoning abilities.

Analogy:
- Data = Books in a library  
- Model = Student learning from those books  

Both elements are interdependent — large datasets need equally capable models to be effective.

Performance vs. Cost Trade-Off

- Larger models generally perform better, but they're expensive:
  - Data collection costs
  - Infrastructure (GPUs, cloud compute)
- Example: GPT-4's training exceeded $100 million.

Importance of Budgeting

Before training, plan your budget carefully:
- Decide how much to invest in:
  - Data gathering
  - Computing power
- Most organizations can only afford to train once — failure is costly.

Smaller Models as a Strategy

- Specialized, smaller models:
  - Are more affordable
  - Easier to fine-tune
  - Well-suited to narrow, fast-changing use cases

---

Latency in Customer-Facing AI Applications

Why Latency Matters

- Users expect instant responses.
- Business applications (e.g., productivity tools) are highly sensitive to delay:
  - Slow AI → Frustration → Drop-off → Revenue loss

Challenge with LLMs

- LLMs use autoregressive generation:
  - Each token is generated in order, one after another.
  - Example: A sentence like "My favorite sport is basketball" at 0.2s/token = 1+ seconds.

Key Limitation: Outputs can't be parallelized — each word depends on the one before.

Strategies to Reduce Latency

Explore New Architectures
- Research is ongoing into models that can generate outputs in parallel.

Optimize Model Size
- Smaller models:
  - Respond faster
  - Often provide “good enough” performance
  - Are more viable for real-time systems

---

Challenges in Scaling Future Language Models (LLMs)

Data Exhaustion

- GPT-4 has already trained on much of the internet's public content.
- GPT-5+ may struggle to find new, high-quality data.

AI-Generated Content Pollution

- The web is filling up with AI-generated content.
- This leads to:
  - Repetition
  - Derivative outputs
  - Increased hallucinations and biases in training

Legal and Policy Barriers

- Media orgs like The New York Times, Shutterstock, etc., have taken legal steps to block data scraping.
- Platforms like Reddit and Quora have revised their terms to restrict access.

Response from OpenAI

- OpenAI is licensing data from content providers.
- Deals include:
  - Shutterstock
  - Axel Springer
  - Associated Press
- Annual costs range from $1M to $5M for premium data access.
