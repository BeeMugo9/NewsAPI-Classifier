# NewsAPI-Classifier
This repository holds the complete deliverables for Part 2 of the MSF recruitment test: a Python notebook that retrieves news articles from the public NewsAPI about humanitarian and medical situations in selected countries

What the notebook does

The notebook runs eight targeted search queries against the NewsAPI free tier, covering MSF operational countries including South Sudan, DRC, Yemen, Syria, Afghanistan, Somalia, Nigeria, Ethiopia, Central African Republic, and Niger. For each article retrieved it extracts five fields (title, source, date, description, URL), assigns a category using keyword scoring, and adds a sentiment label using TextBlob. Results are exported as both CSV and JSON.

Categories assigned: Health and Disease · Conflict and Security · Natural Disaster · Humanitarian Response · General

Limitations

1. Keyword matching cannot capture synonyms or meaning — a semantic LLM classifier would improve accuracy
2. NewsAPI free tier limits queries to the past 30 days and 100 requests per day
3. Results are in English only — French and Arabic reporting is not capture
