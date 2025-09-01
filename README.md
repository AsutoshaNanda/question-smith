
# Question-Smith

A flexible interactive notebook aimed at helping users build a tool that takes technical questions and returns beginner‑friendly explanations using intelligent language models.

---

## Repository Structure

```
├── LICENSE
├── Project 4.ipynb
└── README.md
```

### LICENSE

This is the standard **Apache License 2.0**, granting rights to use, modify, and distribute the project under specified conditions. It provides the legal framework for contributions, derivative works, and redistribution. ([uithub.com][1])

### Project 4.ipynb

A Jupyter notebook designed as a guided exercise for users learning to build an AI-powered tool. It walks through:

* Setting up environment variables and verifying the OpenAI API key.
* Defining model constants like `gpt-4o-mini` and `llama3.2`.
* Crafting system prompts to roleplay a programming tutor that explains technical concepts in beginner‑friendly language.
* Implementing a mechanism to stream responses from an OpenAI-like model via `yield from`.
* Supporting both OpenAI and Ollama backends for inference flexibility.

This notebook structures the technical scaffolding while also demonstrating best practices for clean prompt engineering and API integration. ([uithub.com][1])

---

## Overview & Purpose

**question-smith** is intended to be an instructional and foundational tool for anyone looking to learn how to:

* Interface with large language models (LLMs) like OpenAI’s GPT series and open-source alternatives like LLaMA.
* Engineer system and user prompts to create a task-specific assistant (a programming tutor, in this case).
* Implement streaming responses for responsive and interactive output.
* Facilitate beginner-friendly explanations, breaking down complex code into easy-to-understand steps.

---

## Target Audience

Ideal for:

* Educators and learners in prompt engineering or AI-integrated programming education.
* Developers building tools that convert technical queries into accessible explanations.
* Users exploring hybrid architectures that blend proprietary models (OpenAI) and open-source frameworks (Ollama).

---

## Key Features

* **API Key Validation**: Sets up and validates environment variables to guarantee smooth integration and user feedback. ([uithub.com][1])
* **Model Flexibility**: Supports both GPT-based proprietary models and local LLaMA models via Ollama.
* **Prompt Templates**: Includes system prompts defining tutor behavior and user prompts for simplicity and clarity.
* **Streamed Responses**: Implements a streaming approach with `yield from` for dynamic, responsive output.
* **Beginner-Focused**: Prioritizes clear, jargon-free explanations using Markdown formatting.

---

## How to Get Started

1. **Clone the repository** and open `Project 4.ipynb` in a Jupyter environment.
2. **Set your OpenAI API key** using a `.env` file or environment variable (e.g., `OPENAI_API_KEY`).
3. **Run through** the notebook step by step:

   * Validate the API key and environment setup.
   * Adjust or experiment with system prompts to fine-tune the teaching style.
   * Try both the OpenAI and Ollama backends to compare responses.
4. **Explore and extend**:

   * Change the prompt to tutor in different languages, disciplines, or difficulty levels.
   * Swap out models or add more logic (e.g., caching, error handling, advanced prompt structures).
   * Integrate with other interfaces or UIs (e.g., web apps, chat interfaces).

---

## Why It Matters

This project offers a **practical, hands-on introduction** to constructing AI-powered tutoring tools:

* **Bridges coding and pedagogy**: Demonstrates how to structure prompts that teach as well as compute.
* **Models flexibility**: Showcases how to switch between commercial and open-source LLMs.
* **User-first clarity**: Emphasizes compassionate, clear communication—essential for teaching technical topics effectively.

---

## License

Distributed under the **Apache License 2.0**, allowing for broad use and contribution under defined terms. ([uithub.com][1])

---

## Contributing

Interested contributors can:

* Improve the tutorial prompt structure for different learning styles.
* Add support for additional models or backends (e.g., local CPU-only setups, new open-source LLMs).
* Enhance usability by integrating visualization tools or interactive front-end components.
* Expand explanation templates to cover more domains beyond code (e.g., math, data science, algorithms).

---

### Summary Table

| Component       | Purpose                                                  |
| --------------- | -------------------------------------------------------- |
| LICENSE         | Legal usage and distribution terms                       |
| Project 4.ipynb | Main educational notebook and experimentation playground |
| README.md       | High-level orientation and usage guidelines              |

---
Feel Free to Contribute by improving this Question-Smith
