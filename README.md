<h2 align="center">Exploratory Text Analysis on Charles Dickens and Mark Twain Novels</h2>
<p align="center"><strong>DS5001 Final Project in University of Virginia's Masters in Data Science program</strong>


<h2>About</h2>
The notebook takes raw text files of eight novels by Charles Dickens and Mark Twain (4 from each other) from Project Gutenberg and converts them into a preliminary table with each paragraph in one row (DOC). It also creates another table containing basic information about the novels, such as title and author (LIB). It then annotates the tables into two more tables, TOKEN and VOCAB, containing information about the terms used in all of the novels. After cleaning the data to remove punctuations, numbers, and insignificant terms (using TFIDF values) it further annotates the tables using:

- PCA
- topic models
- word2vec

<h2>Key Learnings</h2>

- Other than Great Expectations, Oliver Twist and A Tramp Abroad, The Innocents Abroad, no other novels shared similar topics
- Innocent Abroad and A Tramp Abroad fit most of the topics pretty well while Adventure of Huckleberry Finn only fit a very few topics well
- Based on the terms used in the novels, racism was definitely prominent during the times the books were written
- Charles Dicken's novels seem to be focused around historical scenes
- Mark Twain's novels seem to be focused more around "coming-of-age" and traveling

<h2>Contents</h2>

- DS5001FinalProject: Jupyter notebook along with the source text files of the novels
  - Use <a href="https://nbviewer.jupyter.org/" target="_blank">nbviewer</a> in case of error when trying to view notebook on github
- ebooks: Source .txt files used in the notebook
- ProjectManifest: Information on the source files and where they can be found
- OutputFiles: output tables generated from the jupyter notebook

<h2>Future Improvements</h2>

- Dynamically retrieve novels from Project Gutenberg
- Automatically read in the novels into LIB and DOC tables without the need for a dictionary
- Create a UI which allows users to select novels from any source

<h2>Credits</h2>

- Author: <a href="https://www.linkedin.com/in/briannam713/" target="_blank">Brian Nam</a>
- eBooks from <a href="https://www.gutenberg.org/" target="_blank">Project Gutenberg</a>
