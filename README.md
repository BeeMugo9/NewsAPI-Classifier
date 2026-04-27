# NewsAPI-Classifier
This repository holds the complete deliverables for Part 2 of the MSF recruitment test: a Python notebook that retrieves news articles from the public NewsAPI about humanitarian and medical situations in selected countries
FileDescriptionMSF_Part2_NewsAPI_Classifier.ipynbWorking Python notebook — the main deliverablemsf_humanitarian_news_classified.csvStructured output with extracted fields and classificationmsf_humanitarian_news_classified.jsonSame output in JSON formatMSF_Part2_Explanation.htmlExported HTML view of the completed notebook

What the notebook does

The notebook runs eight targeted search queries against the NewsAPI free tier, covering MSF operational countries including South Sudan, DRC, Yemen, Syria, Afghanistan, Somalia, Nigeria, Ethiopia, Central African Republic, and Niger. For each article retrieved it extracts five fields (title, source, date, description, URL), assigns a category using keyword scoring, and adds a sentiment label using TextBlob. Results are exported as both CSV and JSON.

Categories assigned: Health and Disease · Conflict and Security · Natural Disaster · Humanitarian Response · General
