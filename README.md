# NLP_ScientificPapers

Welcome to my journey to decode academic papers in on two research streams: the acceptance of new ideas and the impact of social networks on the careers of men and women. This repository contains two notebooks that document my preparation for my PhD comprehensive exam. Each notebook takes a deep dive into different NLP techniques, aiming to uncover the thematic structures within a collection of over a hundred research papers. 


## Inside this repository

- `TF_IDF_Weighted_Log_Odds.Rmd`/`.html`: 
  
  - What it does: This notebook extracts metadata from academic citations and dives deep into the abstracts to pinpoint key terms using TF-IDF and weighted log odds. It specifically highlights distinctive terms within the "Novelty Reception" and "Network and Gender" research streams.
  - Why it's useful: It helps illuminate the specific language and themes that are most pivotal in these streams of academic research.

- `LDA_Topic_Models.qmd`/`.html`:     

  - What it does: Advances our textual analysis by employing Latent Dirichlet Allocation (LDA) for topic modeling.
  - Process:
    - Transform text data, preparing it for deeper analysis.
    - Construct a document-term matrix to serve as the foundation for topic models.
    - Train a range of models (up to 130 topics) to determine the best fit based on thematic coherence.
    - Deliver insights through detailed analysis and visualizations of topic prevalence and coherence.
    - Investigate how different topics relate and cluster together using a dendrogram, offering a visual representation of topic relationships based on their co-occurrence within documents.

To fully engage with the findings, please open the `.html` files in a web browser.

## Replicability 

- Open Data: The dataset analyzed can be accessed through a Google Sheets link provided in the first notebook. Thus, anyone can replicate the study by simply running the provided code.
- Pre-trained Models: To save you time and computational resources, I've included the models trained in the second notebook as well.

