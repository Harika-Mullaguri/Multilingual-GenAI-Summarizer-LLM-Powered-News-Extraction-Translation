# Multilingual-GenAI-Summarizer-LLM-Powered-News-Extraction-Translation
This GenAI app uses BLOOM-1B1 for zero-shot news summarization and translation. It features a hybrid architecture using BLOOM with a MarianMT fallback to ensure accuracy in Hindi, French, and Spanish. Integrated with Newspaper3k for scraping and Gradio for the UI, it delivers a seamless, production-ready experience.
Key Features:
Dual-Model Architecture: Utilizes BLOOM-1b1 for creative summarization and Helsinki-NLP (MarianMT) as a deterministic fallback for high-fidelity translation.
Automated Content Ingestion: Integrated Newspaper3k to handle asynchronous web scraping and boilerplate removal (ads, headers, etc.) from live URLs.
Heuristic Output Validation: Implemented a langdetect verification layer to ensure translation quality, triggering fallback models if the primary LLM fails language consistency.
Cloud-Ready UI: Built an interactive dashboard using Gradio for real-time inference and model comparison
