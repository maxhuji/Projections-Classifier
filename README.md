# Projections-Classifier
This is a supervised machine learning classifier that can be used to identify political projections in large amounts of text data. The classifier was trained on 10.000 manually annotated text segments from various news media outlets and twitter content sampled around the topic of the US 2016 and 2020 Presidential Elections. The segments consist of 5-sentence windows, built around a core-sentence containing relevant future-oriented keywords that may potentially express a political projection. The streamlined coding task asked coders to evaluate whether the core-sentence does indeed contain a political projection. Further coding instructions can be assessed in the supplementary material of the article: Beyond Sentiment: An algorithmic strategy to identify evaluations in large text corpora. 

# PROFECI Projections Classifier
The repository contains the scripts, data files, and additional material that were used to classify projections within large text corpora. Further documentation to the developed approach can be accessed in the article “Beyond Sentiment: An algorithmic strategy for identifying evaluations within large text corpora" published in Communication Methods and Measures.

To cite: 
Overbeck, M., Baden, C., Aharoni, T., Amit-Danhi, E., & Tenenboim Weinblatt, K. (2023). Beyond sentiment: An algorithmic strategy for identifying evaluations within large text corpora. Communication Methods and Measures, 1–22. https://doi.org/10.1080/19312458.2023.2285783
Tenenboim-Weinblatt, K., Baden, C., Aharoni, T., Overbeck, M., & Amit-Danhi, E. R. (2021). PROFECI Codebook: Israeli Elections 2019-2021 & US Elections 2016/2020. PROFECI Working Paper 02-2021. Jerusalem, Israel: The Hebrew University of Jerusalem. http://profeci.net/PROFECI%20Working%20Paper%2002-2021%20Codebook.pdf

In this repository you fill find the following material: 
1. The supplementary material.docx file that provides further details on the various steps and dictionaries used in the pre-processing, and the codebook used for the manual annotation.
2. The Classifications_Input.xlsx dataset that is required to train the projections classifier (based on 10.000 manually annotated segments), and to test its performance against the Gold Standard (1.637 manually annotated segments). 
3. The Script to train and test the performance of the projections classifier on the English corpus. 
4. The Script to train and test the performance of the projections classifier on the French and Hebrew corpus.
5. The Script to run the projections classifier on new snippets. 

