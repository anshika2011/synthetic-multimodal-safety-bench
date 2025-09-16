This project builds a synthetic dataset + evaluation pipeline to test vision-language models (VLMs) on tricky or adversarial cases, such as:
- Charts with misleading scales (e.g., truncated Y-axis exaggerating trends)
- Look-alike objects (wolf vs husky, mug vs bowl)
- Captions that are subtly wrong (“Profits are skyrocketing!” when they aren’t)
All examples are stored with embeddings + metadata in a vector database (FAISS), so you can flexibly query things like:
“Show me all misleading chart cases.”
