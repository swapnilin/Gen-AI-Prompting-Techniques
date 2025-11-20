# Gen-AI- LLM-Prompting-Techniques

This repository contains an interactive Jupyter Notebook (`.ipynb`) designed to explore and demonstrate **advanced prompt engineering techniques** using the latest **Gemini 2.0 API**.

### Key Features

* **Hands-on Examples:** Provides practical, executable code snippets for several high-impact prompting strategies.
* **Core Techniques Covered:** Dive into essential methods that significantly improve model output quality, consistency, and control. This notebook provides practical demonstrations for:
    * **Context Setting:**
        * **Zero-Shot:** Basic prompts relying purely on the model's pre-trained knowledge.
        * **One-Shot / Few-Shot:** Conditioning the model with one or more input/output examples to define the desired response style and format.
    * **Reasoning and Process Control:**
        * **Chain-of-Thought (CoT):** Instructing the model to show its step-by-step reasoning for complex problem-solving.
        * **ReACT:** Using iterative **Reasoning** and **Action** steps for agent-like behavior and tool use.
        * **Reason / Thinking Mode:** Explicitly prompting the model to engage in deeper, reflective processing before generating the final answer.
    * **Formatting and Structure:**
        * **Structured Output (JSON/Pydantic):** Techniques for forcing machine-readable data structures.
        * **Enum Mode:** Instructions for formatting outputs as clear, ordered or unordered lists (enumerations).

* **Gemini 2.0 Optimization:** All examples are optimized for the **Google Gemini family of models**, showcasing features like multi-modal input and configuration options to maximize performance and efficiency.

### Prerequisites

To run the notebook, you need:

1.  **Python 3.9+** installed.
2.  A **Gemini API Key**. You can generate one from [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key).
