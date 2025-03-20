# 4th_Sem_Innovative_Project:-


📌 Project Overview:-

This project extracts key legal sections from three major acts:
Negotiable Instruments Act (NIA), 1881
Dowry Prohibition Act, 1961
Copyright Act, 1957
The extracted six sections are then structured and converted into JSON format for easy analysis and retrieval.


🚀 Features:-

LEVEL1:-
✅ Extracts key sections from three different legal acts.
✅ Cleans and formats legal text for better readability.
✅ Converts structured data into JSON format for efficient storage.

LEVEL2:-
✅ Removes stopwords and unnecessary text for concise content.


🛠️ Tech Stack:-

Python 🐍 (For text extraction & processing)
JSON 📂 (For structured data storage)
NLTK / Scikit-Learn 🧠 (For text preprocessing)


🔧 How It Works:-

Extract Legal Text: Parse six sections from the three acts.
Convert to JSON: Store structured sections in key-value format.
Preprocess Content: Remove stopwords & special characters.
Save Output: Generate a clean JSON file for further use.


📂 Project Structure:-

/legal-acts-json-extractor
│── data/
│   ├── nia_sections.json
│   ├── dowry_sections.json
│   ├── copyrights_sections.json
│── scripts/
│   ├── extract_sections.py   # Extracts sections from acts
│   ├── clean_text.py         # Removes stopwords & formats content
│   ├── convert_to_json.py    # Saves structured data as JSON
│── README.md                 # Project documentation


LEVEL 3:-

🚀 A structured Knowledge Graph (KG) representation of legal sections from three major acts:
1️⃣ Negotiable Instruments Act, 1881 (NIA)
2️⃣ Dowry Prohibition Act, 1961
3️⃣ Copyright Act, 1957

This project transforms raw legal text into a semantic RDF-based Knowledge Graph, allowing structured queries and advanced legal analytics.


✅ Extracts key sections from three legal acts
✅ Creates RDF-based Knowledge Graph with structured relationships
✅ Includes content theory classification (e.g., Criminal Law, Contract Law)
✅ Compatible with Neo4j, Apache Jena, and GraphDB
✅ Supports SPARQL queries for advanced retrieval


🛠️ Technologies Used:-

🔹 Python 🐍 (for JSON processing and RDF generation)
🔹 RDFLib 📖 (for semantic graph construction)
🔹 SPARQL 🔎 (for querying legal data)
🔹 Neo4j / Apache Jena 🛢️ (for graph database storage)


📂 Project Structure:-

/legal-acts-kg
│── data/
│   ├── nia_refined.json
│   ├── dowry_refined.json
│   ├── copyrights_refined.json
│── rdf_output/
│   ├── legal_acts_kg.ttl  # Full Knowledge Graph in Turtle format
│── scripts/
│   ├── json_to_kg.py      # Converts JSON to RDF
│   ├── sparql_queries.txt  # Sample SPARQL queries
│── README.md              # Project documentation


📊 Knowledge Graph Structure:-

Classes (rdf:type)
Act → Represents each legal act
Section → Represents individual sections
Content → Stores the full text of a section
ContentTheory → Classifies the section under a legal domain
Properties (rdf:Property)
sectionNumber → Section number
title → Section title
belongsToAct → Links sections to their respective acts
hasContent → Links section to its legal text
hasTheory → Links section to its legal classification
theory → Stores the legal domain of the section


AUTHORS:-

1.)ARMAAN VASAL (523110039)
2.)SHUBHAM KUMAR SHAW (523110001)
3.)SAKSHAM SINGH (523110010)
