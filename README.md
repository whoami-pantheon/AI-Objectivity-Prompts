# AI-Driven Development Framework


## Author

*   **Name:** Clive Akporube
*   **GitHub:** [whoami-pantheon](https://github.com/whoami-pantheon)
*   **LinkedIn:** [Clive (Kaiser) Akporube](https://linkedin.com/in/clive-kaiser)


## Summary

This repository contains a curated suite of advanced system prompts engineered to leverage Large Language Models (LLMs) for strategic software development and objective analysis. The primary goal is to create force-multiplying tools that standardize and accelerate the process of system architecture, code generation, and complex reasoning while embedding security and best practices from the outset.

## Vision

The future of software development will involve a symbiotic partnership between human experts and AI. This framework is a step toward that future; a structured approach to AI-driven development that prioritizes precision, security, and strategic alignment. By using sophisticated, chained prompts, we can guide AI models to perform highly complex tasks, transforming them from general-purpose assistants into specialized, virtual team members.

## Core Projects

### Project Lattice: The Objective Reasoning Partner

Project Lattice transforms a standard AI assistant into a rigorous, objective reasoning partner. Its goal is not to provide comforting answers but to stress-test ideas, identify logical flaws, and surface non-obvious connections. It prioritizes cold, hard truth over agreement, making it an invaluable tool for personal growth, strategic thinking, and decision-making.

- **`Project Lattice v1.0 AI Prompt.txt`**: The initial version focused on establishing a baseline of objectivity. It instructs the AI to hold its ground, avoid servility and moralizing, and test the user's reasoning.

- **`Project Lattice v2.0 AI Prompt.txt`**: A more advanced and structured evolution of v1.0. This prompt directs the AI to perform deeper analysis, identifying second-order effects, structural asymmetries, and flawed mental frames. It's designed to sharpen the user's foresight and strategic capabilities.


### Project Mother: The Secure System Architect & Builder

Project Mother is a powerful two-stage pipeline that turns a high-level concept into a fully-specified, security-hardened software system. The reason for the two-stage approach is to leverage the unique strengths of two different Gemini models: one for high-level architecture and one for implementation.


- **Stage 1: The Architect (Gemini 2.5)**: This prompt directs a model like Gemini 2.5 Pro, which excels at systems thinking, to act as a senior systems architect. It takes a user's idea and generates a comprehensive, deterministic specification, and unambiguous system specification that includes foundational **Security Requirements** and a **Threat Model** from the very beginning. 

- **Stage 2: The Builder (Gemini 3)**: This prompt is designed for the Google Antigravity IDE, which utilizes the Gemini 3 model for high-fidelity code generation. It takes the architect's blueprint and materializes it into a working Python application, explicitly adhering to **secure coding practices** and including security tools like `bandit` and `safety` in the project.

## Security & Risk Considerations

Risk considerations requires a security-first posture, especially when dealing with automation and AI. This framework is designed with that in mind.

### Principle of Human Oversight

The output of these prompts, particularly generated code and architecture, must be treated as a first draft produced by a highly-skilled but non-authoritative junior partner. **All AI-generated artifacts require rigorous human expert review, security auditing, and validation before being considered for production environments.**

### Security by Design

This framework embeds security into the earliest stages of the development lifecycle. By including `Security Requirements`, `Threat Model`, and secure coding instructions directly in the prompts, we shift security to the left, making it a foundational component of the system rather than an afterthought.

## Operational Procedure

1.  **Select a Prompt**: Choose the project file that matches your strategic goal.
2.  **Initiate Session**: Copy the entire content of the chosen prompt file.
3.  **Paste as First Message**: In a new session with the appropriate AI model (e.g., ChatGPT-4, Gemini 2.5 Pro, Google Antigravity IDE), paste the copied content as the initial instruction. For persistence, you can also add it to custom instructions or instructions for Gemini. After this, you won't need to paste it again, it'll persist in new conversations.
4.  **Provide Input**:
    - For **Project Lattice**, you can begin conversing with the AI immediately after the initial prompt.
    - For **Project Mother**, append your idea where the prompt indicates `<INPUT YOUR IDEA>`. For the second stage, paste the output from the first prompt where it says `<PASTE THE GEMINI 2.5 PRO OUTPUT HERE>`.



## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.                                                                                                                                                 
