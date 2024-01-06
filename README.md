# Data Extraction and NLP
The objective of this project is to extract textual data articles from the input file cantaining URL's and perform text analysis to compute variables that are explained below. 
# Demo link
If you have a working demo of the project, provide the link so that readers can see your project in action.
# Table of contant
1. Data Extraction  
Input.xlsx
For each of the articles, given in the input.xlsx file, extract the article text and save the extracted article in a text file with URL_ID as its file name.
While extracting text, please make sure your program extracts only the article title and the article text. It should not extract the website header, footer, or anything other than the article text.
2. Data Analysis  
For each of the extracted texts from the article, perform textual analysis and compute variables, given in the output structure excel file. You need to save the output in the exact order as given in the output structure file, “Output Data Structure.xlsx”
3. Variables  
Find:  
\-POSITIVE SCORE\
\-NEGATIVE SCORE\
\-POLARITY SCORE\
\-SUBJECTIVITY SCORE\
\-AVG SENTENCE LENGTH\
\-PERCENTAGE OF COMPLEX WORDS\
\-FOG INDEX\
\-AVG NUMBER OF WORDS PER SENTENCE\
\-COMPLEX WORD COUNT\
\-WORD COUNT\
\-SYLLABLE PER WORD\
\-PERSONAL PRONOUNS\
\-AVG WORD LENGTH\
4. Output Data Structure
Output Variables: 
All input variables in “Input.xlsx”
POSITIVE SCORE
NEGATIVE SCORE
POLARITY SCORE
SUBJECTIVITY SCORE
AVG SENTENCE LENGTH
PERCENTAGE OF COMPLEX WORDS
FOG INDEX
AVG NUMBER OF WORDS PER SENTENCE
COMPLEX WORD COUNT
WORD COUNT
SYLLABLE PER WORD
PERSONAL PRONOUNS
AVG WORD LENGTH
Check out the output data structure spreadsheet for the format of your output, i.e. “Output.xlsx”.

# Business understanding
The goal of this project is to leverage the power of text analysis on a set of articles. The articles are not directly provided but are accessible through a list of URLs contained in an input file.

The primary objective is to extract the textual data from these articles and perform a comprehensive text analysis. This analysis aims to compute specific variables, which will be explained in the subsequent sections.

The motivation behind selecting this project was the growing importance and ubiquity of data, particularly unstructured text data, in today’s digital age. Text analysis allows us to extract meaningful insights and patterns that can inform decision-making processes, making it a valuable tool in various fields such as marketing, politics, social sciences, and more.

As for the challenges faced during the project, they were mainly around the extraction of clean, usable text from the articles. Web articles often contain a lot of additional information such as ads, headers, footers, and more, which are not relevant to the analysis. Therefore, a significant part of the project was dedicated to preprocessing and cleaning the data to ensure the accuracy of the analysis.

Another challenge was dealing with the vast and diverse nature of text data. Unlike structured data, text data can be highly variable and context-dependent, which adds a layer of complexity to the analysis. However, overcoming these challenges provided valuable learning experiences and made the success of the project even more rewarding.

In conclusion, despite the challenges, this project was an exciting journey into the world of text analysis. The insights derived from the project have the potential to be highly impactful and can pave the way for further research in this field.

# Data Understanding
The data for this project was sourced from a variety of online articles. These articles were not directly provided but were accessed through a list of URLs contained in an input file. The choice of this data set was motivated by several factors:

Diversity: Online articles cover a wide range of topics, styles, and perspectives. This diversity is beneficial for a text analysis project as it allows the model to capture a broad spectrum of language use.

Accessibility: Web articles are publicly available and easily accessible, making them a convenient choice for data collection.

Relevance: Given the digital nature of today’s world, understanding and analyzing online text data is highly relevant and practical.

As for future enhancements or additional analysis, there are several possibilities:

Sentiment Analysis: This involves determining the sentiment expressed in the text data, which can be particularly useful for understanding public opinion on certain topics.

Topic Modeling: This is a type of statistical model used for discovering the abstract “topics” that occur in a collection of documents.

Named Entity Recognition (NER): This is a process where you extract elements such as names of people, organizations, places, date expressions, and quantities from the text.

Expanding the Data Set: To improve the robustness of the analysis, the data set could be expanded to include more articles or other types of text data.

Time Series Analysis: If the articles are timestamped, it would be interesting to perform a time series analysis to understand how language use or topics of interest change over time.

These enhancements would not only add depth to the current analysis but also open up new avenues of exploration and understanding. They represent exciting opportunities for future work in the field of text analysis.
# Screenshort of visuallization/Results
Examples of the process or outputs. In analytics, these can be images of visualizations.
# Tecnologies
The completion of the project involved the use of several technologies, demonstrating proficiency in a variety of tools. Here’s a list of the key technologies used:

Python: Python was the primary programming language used for this project. Its extensive library support and easy-to-read syntax make it a popular choice for data analysis projects.

Pandas: This Python library was used for data manipulation and analysis. It provides data structures and functions needed to manipulate structured data.

NumPy: Another Python library, NumPy was used for numerical computations.

BeautifulSoup: This Python library was used for web scraping purposes to extract the articles from the provided URLs.

NLTK (Natural Language Toolkit): This is a Python library used for working with human language data. It provides easy-to-use interfaces for over 50 corpora and lexical resources.

Scikit-learn: This Python library was used for machine learning and statistical modeling including classification, regression, clustering, and dimensionality reduction.

Jupyter Notebook: Jupyter Notebook was used as the IDE (Integrated Development Environment) for coding in Python and presenting the results.

GitHub: GitHub was used for version control and source code management.

These technologies were instrumental in the successful completion of the project, and I am proficient in using these tools. They represent a small subset of the tools available for data analysis and text processing, and I’m always open to learning and using new technologies as required by the project.
# Setup
Install Necessary Libraries: Once your virtual environment is activated, you can install the necessary libraries using pip, Python’s package installer. The command is generally in the format:
pip install library-name

# approach
Data Extraction: Use a web scraping tool or library (such as BeautifulSoup, Scrapy, or Selenium) to fetch the web pages from the given URLs and parse the HTML content. Identify the elements that contain the article title and text, and extract them using CSS selectors or XPath expressions. Save the extracted article in a text file with URL_ID as its file name.

Data Analysis: Use a natural language processing (NLP) tool or library (such as NLTK, spaCy, or TextBlob) to perform textual analysis on the extracted articles. Compute the variables given in the output structure file using various NLP techniques, such as sentiment analysis, readability scores, word counts, syllable counts, etc. Save the output in a spreadsheet file with the same format as the output structure file.

Data Visualization: Use a data visualization tool or library (such as Matplotlib, Seaborn, or Plotly) to create charts or graphs that show the distribution or relationship of the variables computed in the data analysis step. For example, you can plot a histogram of the polarity scores, a scatter plot of the word count vs. the fog index, or a bar chart of the personal pronouns. Save the visualizations in an image file or a PDF file.
# Status
complete/released
# Credits
I would like to acknowledge the assistance of Microsoft Bing in this project. Bing’s chat mode is a remarkable tool that can generate various types of content, such as code and more. Bing’s chat mode also helped me with writing, rewriting, improving, or optimizing my content. Bing’s chat mode can understand and communicate fluently in the user’s language of choice, and can also create graphical artworks based on user’s prompts, and perform web searches to provide relevant information.
