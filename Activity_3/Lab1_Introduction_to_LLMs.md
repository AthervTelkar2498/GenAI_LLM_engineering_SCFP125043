# Lab 1 — Introduction to LLMs: Practical Activities

## GitHub Repository Setup

Create a GitHub repository named `generative_ai_<student-name-or-roll-no>`. All activity work goes into this one repository, pushed after each activity.

---

## Activity 1 — Explore LLM Models on Hugging Face

Pick three models on Hugging Face — one small, one medium, one large.

- Who created the model?
- How many parameters does it have?
- Is it a generative model?
- What is the context length?
- Is the model suitable for local execution?
- What hardware does the model card recommend?

**Upload to GitHub.**

---

## Activity 2 — Tokenization Practical

Tokenize a sentence, then try a few different words and phrases.

- Is one word always one token?
- Why are some words split?
- What happens to punctuation?
- Why does the model need token IDs?

**Upload to GitHub.**

---

## Activity 3 — Run an LLM Using Google Colab GPU

Enable a GPU runtime and run a small model.

- Is the GPU actually being used?
- How much memory does the model consume?
- What happens if you increase the output length?
- Would this run on a laptop without a GPU?

**Upload to GitHub.**

---

## Activity 4 — Can My Computer Run an LLM?

Check your RAM and GPU, then estimate memory needs at different precisions.

- Your laptop has 8 GB RAM — 4B FP16, 4B INT4, or 7B INT4? Why?
- What else besides model weights uses memory?
- Would quantization always be the safer choice? Why or why not?

**Upload to GitHub.**

---

## Activity 5 — Run an LLM Locally Using Ollama

Install Ollama and run a model locally.

- Does the model need internet after downloading?
- Where is inference actually happening?
- Is any data leaving your machine?
- What happens if the model is too large for your memory?

**Upload to GitHub.**

---

## Activity 6 — Use an LLM Through an API / Inference Provider

Call a model through an API provider.

- What is actually happening between your program and the model?
- Who is paying for compute here?
- What are the trade-offs versus running locally?

**Upload to GitHub.**

---

## Activity 7 — Compare Local vs Colab vs API

- If you had an 8 GB RAM laptop with no GPU, which approach would you pick?
- Which approach is most private? Which is most scalable?
- When would you choose local over cloud, or the reverse?

**Upload to GitHub.**

---

## Activity 8 — Temperature Experiment

Run the same prompt at temperature 0.1, 0.7, and 1.0.

- Which output felt most predictable? Most creative?
- Does temperature change what the model knows?
- When would you want low temperature? High temperature?

**Upload to GitHub.**

---

## Activity 9 — Build a Mini Chatbot

Build a chatbot loop using Ollama or an API provider, keeping conversation history.

- Why does the chatbot need to remember previous messages?
- What happens if you drop the conversation history?
- What's the difference between this and a single one-off prompt?

**Upload to GitHub.**

---

## Activity 10 — Customize the Chatbot

Give your chatbot a role, such as an AI/ML tutor.

- How did the responses change compared to Activity 9?
- Could the same model behave like a completely different assistant just from the instructions you gave it?
- What role would you build next, and why?

**Upload to GitHub.**

---

## Final Submission

Push all activity work to `generative_ai_<student-name-or-roll-no>` and share the repository link:

```text
https://github.com/<username>/generative_ai_<student-name-or-roll-no>
```
