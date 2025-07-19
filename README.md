# 🎬 Data612 Final Project — Hybrid Movie Recommender with Azure OpenAI

## 📌 Overview
This project is the final deliverable for Data612 (Recommender Systems). Throughout this course, I explored, implemented, and evaluated several recommendation algorithms using the MovieLens dataset.

I built:
- **Model-based CF:** ALS (Alternating Least Squares)
- **Memory-based CF:** Item-Item and User-User kNN
- **Content-based filtering:** using movie metadata and taglines
- **LLM-based prototype:** leveraging Azure OpenAI GPT-4 for free-text suggestions

## ⚙️ Techniques Used
- PySpark for large-scale matrix factorization and similarity calculations
- Cosine similarity for neighborhood models
- BeautifulSoup for web scraping extra metadata (taglines)
- Azure OpenAI for cloud-based generative recommendations

## 📊 Evaluation Metrics
- Precision@10
- MAP@10
- Diversity@10
- Novelty@10
- LLM output matched back to test set for Precision & Recall

## ✨ Key Takeaways
- Hybrid pipelines that combine CF, content, and generative AI can boost explainability and creativity.
- LLM-based recommendations can supplement structured models with free-text, thematic suggestions — but matching them back to a known catalog requires richer metadata.
- This project directly inspired my future **Capstone goal**: building an intelligent classroom recommender to support my own students, starting in 2025–2026.

## 🔭 Next Steps
- Expand movie metadata with TMDB or IMDB IDs to improve LLM match rates.
- Combine LLM output with ALS/kNN reranking for more relevant suggestions.
- Use LLM explanations for human-friendly recommendation justifications.

## 🙏 Acknowledgment
Thank you to Professor Kowalchuk for an engaging, inspiring semester!

---

**Author:** Saloua Daouki  
**Course:** Data612 — Recommender Systems  
**Summer 2025**
