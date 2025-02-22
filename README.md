# Comparative Analysis of Religious Texts: NLP Approaches to the Bible, Quran, and Bhagavad Gita

## Introduction
This repository contains the code and resources for the project **Comparative Analysis of Religious Texts: NLP Approaches to the Bible, Quran, and Bhagavad Gita**, developed by researchers from the National Institute of Technology Karnataka (NITK), Surathkal, India. The project was presented at the **Proceedings of the New Horizons in Computational Linguistics for Religious Texts** conference in Abu Dhabi, UAE, in January 2025.

## Project Overview
This study explores the application of Natural Language Processing (NLP) techniques to analyze and compare the thematic and emotional dimensions of three major religious texts: the Bible, the Quran, and the Bhagavad Gita. By employing advanced NLP methods, the research aims to uncover shared themes, sentiment patterns, and semantic similarities across these sacred texts, offering new insights into their cultural and moral impacts.

## Key Contributions
- **Topic Modeling**: Utilized Latent Dirichlet Allocation (LDA) to identify and compare key themes across the texts.
- **Sentiment Analysis**: Applied Valence Aware Dictionary and sEntiment Reasoner (VADER) to assess the emotional tone of verses.
- **Semantic Comparison**: Employed GloVe embeddings and Sentence Transformers to measure semantic similarities and differences.
- **Corpus Distance Measurement**: Analyzed linguistic and thematic divergence using metrics like Fréchet Inception Distance (FID) and cosine similarity.

## Publication
Our findings were published in the following conference paper:

**[Comparative Analysis of Religious Texts: NLP Approaches to the Bible, Quran, and Bhagavad Gita](https://aclanthology.org/2025.clrel-1.1/)**

A D Mahit Nandan, Ishan Godbole, Pranav Kapparad, and Shrutilipi Bhattacharjee
*Proceedings of the New Horizons in Computational Linguistics for Religious Texts*
January 2025, Abu Dhabi, UAE

### Citation
If you use our work, please cite:
```bibtex
@inproceedings{a-d-etal-2025-comparative,
    title = "Comparative Analysis of Religious Texts: {NLP} Approaches to the {B}ible, {Q}uran, and Bhagavad Gita",
    author = "A D, Mahit Nandan and Godbole, Ishan and M Kapparad, Pranav and Bhattacharjee, Shrutilipi",
    editor = "Yagi, Sane and Yagi, Sane and Sawalha, Majdi and Shawar, Bayan Abu and AlShdaifat, Abdallah T. and Abbas, Norhan and Organizers",
    booktitle = "Proceedings of the New Horizons in Computational Linguistics for Religious Texts",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.clrel-1.1/",
    pages = "1--10",
    abstract = "Religious texts have long influenced cultural, moral, and ethical systems, and have shaped societies for generations. Scriptures like the Bible, the Quran, and the Bhagavad Gita offer insights into fundamental human values and societal norms. Analyzing these texts with advanced methods can help improve our understanding of their significance and the similarities or differences between them. This study uses Natural Language Processing (NLP) techniques to examine these religious texts. Latent Dirichlet Allocation (LDA) is used for topic modeling to explore key themes, while GloVe embeddings and Sentence Transformers are used to compare topics between the texts. Sentiment analysis using Valence Aware Dictionary and sEntiment Reasoner (VADER) assesses the emotional tone of the verses, and corpus distance measurement is done to analyze semantic similarities and differences. The findings reveal unique and shared themes and sentiment patterns across the Bible, the Quran, and the Bhagavad Gita, offering new perspectives in computational religious studies."
}
## Dataset
The study utilized English translations of the Bible, Quran, and Bhagavad Gita. These texts were preprocessed to ensure uniformity for analysis, including text normalization, tokenization, and stop-word removal.

## Methodology
1. **Topic Modeling**: LDA was applied to extract key themes from each text.
2. **Sentiment Analysis**: VADER was used to classify verses into positive, negative, and neutral sentiments.
3. **Semantic Comparison**: GloVe embeddings and Sentence Transformers were used to quantify thematic similarities.
4. **Corpus Distance Measurement**: FID and cosine similarity metrics were employed to analyze semantic and linguistic variations.

## Results
The analysis revealed unique and shared themes across the texts, highlighting their distinct philosophical dialogues and moral imperatives while also uncovering common ethical frameworks and human values.

## Future Work
Future research could expand the scope by including additional religious texts and exploring advanced NLP techniques for more nuanced insights. Longitudinal studies on the evolving interpretations of these texts could also provide a broader view of their continued relevance.

## Team
- **A D Mahit Nandan**
- **Ishan Godbole**
- **Pranav Kapparad**
- **Shrutilipi Bhattacharjee**

Affiliation: National Institute of Technology Karnataka (NITK), Department of Information Technology

---

Thank you for exploring our project! For more details, please refer to our [published paper](https://aclanthology.org/2025.clrel-1.1/).
