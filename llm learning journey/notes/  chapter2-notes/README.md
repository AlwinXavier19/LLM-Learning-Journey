📘 Chapter 02 — Using 🤗 Transformers
📎 Full notes: LLM-Course-Chapter2-Notes.pdf
📌 Overview
This chapter opens the hood on pipeline(): the AutoTokenizer/AutoModel APIs, tokenization strategies, padding/truncation, attention masks, batching, and how production frameworks (TGI, vLLM, llama.cpp) optimize LLM serving.
🧠 Topics Covered
Behind the pipeline — tokenizer → model → postprocess AutoModel — configs, checkpoints, save/load/push_to_hub Tokenizers — word vs. character vs. subword (BPE/WordPiece/SentencePiece) Handling multiple sequences — batching, padding, attention masks Putting it together — the full tokenizer() one-liner Optimized inference deployment — Flash Attention, PagedAttention, TGI, vLLM, llama.cpp, quantization
✅ Key Takeaway
Padding is only safe with an attention mask; logits need softmax before they're probabilities. Serving frameworks (TGI/vLLM/llama.cpp) optimize memory movement and precision — not what the model computes.
🧾 Includes in the PDF
Cheat sheet · glossary · 20 interview Q&As · 20-question quiz · hands-on exercises · revision checklist
Reference: Hugging Face LLM Course — Chapter 2
