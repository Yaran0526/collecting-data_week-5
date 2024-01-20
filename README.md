# Collecting-Data_individual final assignment
## 1. Research Question(optional)
This project uses spacy to analyze the linguistic features of the poetic works of four female writers around the 19th century, such as word choice, syntactic structure, etc., and explore the correlation between these features and female themes (such as self-perception, emotional experience, female identity, etc.).

The importance of this research question is that by analyzing the poetic works of female writers and using spacy for in-depth research, it can help us gain a deeper understanding of female literature, female perspectives, and the manifestation of gender in literary creation. This helps unearth the literary achievements of female writers, expands awareness of female voices and perspectives, and may help eliminate gender bias and promote gender equality in the literary field.

## 2. Brief Description
(1) The corpus itself

This corpus includes 4 files, which are excerpts from poems by 4 female writers. Poetry was chosen as the research object of this project because, among many literary genres, poetry can best reflect the characteristics of language and diction. These four female writers all had an important position in the world literary world in the 19th century.
they are, respectively:

Sonnets from the Portuguese. It is a collection of 44 love sonnets written by the British poet Elizabeth Barrett Browning (1806.3.6-1861.6.29).

Poems written by the British poet Christina Rossetti (1830.12.5-1894.12.29). It contains her famous poem "Goblin Market" and other poetries.

Poems written by American poet Edna St. Vincent Millay (1892.2.22-1950.10.19). Millay won the 1923 Pulitzer Prize for Poetry.

Poems by Emily Dickinson, Series One. This is an excerpt from the first series of her collection of works written by American poet Emily Dickinson (1830.12.10-1886.5.15).

(2) Target audience and the intended use of the corpus

The target audience of this project is lovers and researchers of British and American literature or women's literature.
The analysis of this project will help them understand the characteristics of these four female writers in poetry creation in the form of data analysis.

(3) Text selection criteria

This project selected four of the most representative female writers of the 19th century, namely two British writers and two American writers. The selected works are also the most representative or special works in their creative careers. Due to the space limitations of this project, the entire collection of poems cannot be used, and the previous parts of the collection are excerpted for study.

(4) The data collection process

The text data of the corpus is downloaded from the official website of Project Gutenberg, the URL is https://www.gutenberg.org/

(5) Cleaning and/or preprocessing steps

This project uses regular expressions to remove extra whitespace characters from the text and trim the text to remove leading and trailing spaces. 

(6) Annotations that I’ve added and tools that are used for that

In the code, the Spacy library is used, which provides some NLP functions, including part-of-speech tagging, lemmatization, named entity recognition, etc. Here are the functions and tools used in this code:
Part-of-Speech Tagging: Get the part-of-speech of each word through the token. pos_.
Lemmatization: Use a token. lemma_ to get the token (basic form) of each word.
Named Entity Recognition: Use doc. ents to get named entities in text and recognize their tags.
These tools are applied to a given text for part-of-speech tagging, tokenization, and named entity recognition.

(7) The format of the files in the corpus (in this case, probably Txt and CSV), as well as the description of the columns in the CSV file.

The code handles two file formats: .txt and .csv. The .txt file contains text content, while the .csv file contains metadata information. The CSV file contains some columns, and the code renames one of the columns according to specific needs.

