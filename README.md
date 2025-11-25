# Fossil Fuel Industry Text Analytics

Topic modeling analysis of 50 articles on fossil fuels using Latent Dirichlet Allocation (LDA) to identify key themes and trends in the energy sector.

## 📋 Project Overview

This academic project applies Natural Language Processing (NLP) and topic modeling techniques to analyze content about the fossil fuel industry. The analysis helps stakeholders understand current trends, regulations, and public sentiments to make informed decisions about production and strategy.

## 🎯 Problem Statement

Excessive fossil fuel consumption is driving global climate change and regulatory actions worldwide. This project aims to analyze industry trends and government regulations to help fossil fuel industry stakeholders optimize production and manage regulatory risks.

## 🔧 Methodology

### Data & Tools
- **Dataset**: 50 scraped articles about fossil fuels
- **Techniques**: Latent Dirichlet Allocation (LDA) for topic modeling
- **Libraries**: Gensim, spaCy, NLTK, pyLDAvis
- **Preprocessing**: Tokenization, stopword removal, punctuation cleaning

### Model Evaluation
- **Perplexity Score**: -6.34
- **Coherence Score**: 0.399
- **Optimal Topics**: 2 (determined through coherence score comparison)

## 📊 Key Findings

### Extracted Topics:
- **Topic 0**: Fossil fuel composition & energy production
  - Key words: `power, greenhouse, air, burning, fuel, dioxide, water, natural, carbon`
- **Topic 1**: Environmental impact & health effects
  - Key words: `effects, children, carbon, warming, fuels, health, pollution, emissions, climate`

### Network Insights:
- Most central/connected artist: **Camilla Cabello** (Degree Centrality: 0.157)
- Key bridge artist: **Meghan Trainor** (Betweenness Centrality: 0.336)
- Isolated artist: **Michael Jackson** (Zero connections)

## 📈 Business Implications

- **Risk Management**: Stay updated on evolving regulations and public sentiment
- **Production Optimization**: Adjust output based on market trends and regulatory landscape
- **Strategic Planning**: Identify emerging topics and industry shifts
- **Stakeholder Communication**: Understand public concerns about environmental impact

## 🛠 Technical Implementation

The project includes:
- Text preprocessing and tokenization
- LDA model training and optimization
- Interactive topic visualization using pyLDAvis
- Word cloud generation for key themes
- Document-topic assignment

## 📁 Files Included

- Complete analysis report with methodology
- Code implementation details
- Visualization outputs and word clouds
- Model evaluation metrics

---

*Academic Project | MBA544B - Text and Social Media Analytics | Christ University*
