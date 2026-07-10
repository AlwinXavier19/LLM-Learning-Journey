📘 Chapter 01 — Transformer Models


📎 Full notes: LLM-Course-Chapter1-Notes.pdf




📌 Overview

This chapter covers the foundations everything else builds on: NLP vs. LLMs, the pipeline() API, why Transformers replaced RNNs, transfer learning, attention, encoder/decoder architectures, and bias & limitations.

🧠 Topics Covered


NLP (the field) vs. LLMs (the current dominant tool)
pipeline() — tokenizer → model → postprocess
Transformer history: attention replacing recurrence (2017 → today)
Pretraining vs. fine-tuning
Attention — the core mechanism
Encoder-only / Decoder-only / Encoder-Decoder — which fits which task
Bias & hallucination as structural limitations


✅ Key Takeaway

Task shape decides architecture: understand → encoder, generate → decoder, transform → encoder-decoder. Pretraining is expensive and rare; fine-tuning is cheap because it starts from already-good weights.

🧾 Includes in the PDF

Cheat sheet · glossary · 20 interview Q&As · 20-question quiz · hands-on exercises · revision checklist


Reference: Hugging Face LLM Course — Chapter 1
