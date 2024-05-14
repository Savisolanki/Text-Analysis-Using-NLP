# Text-Analysis-Using-NLP

Data Collection: We began by gathering input data from an Excel file containing the URLs of the articles we intended to evaluate.

Text extraction: We used the requests library to fetch the HTML content of each article URL and then used BeautifulSoup to parse the HTML and extract the article text from <p> tag.

Sentiment Analysis: We used NLTK's VADER sentiment analysis tool to determine the sentiment of the article text. This included calculating positive, negative, polarity, and subjectivity scores.

Text Complexity Analysis: We calculated several metrics to assess the text's complexity, including average sentence length, percentage of complicated words, Fog Index, average number of words per phrase, and complex word count. These indicators can offer information regarding readability and complexity.

Syllable Counting: We used the CMU Pronouncing Dictionary from NLTK to estimate the number of syllables per word in the text. This is useful for calculating readability metrics like the Fog Index.

Personal Pronoun Count: We counted the occurrences of personal pronouns in the text. This can be indicative of the author's writing style and perspective.

Data Analysis and Export: We aggregated the results of our text analysis into a pandas DataFrame and exported the data to a CSV file. This allows for further analysis and visualization of the findings.
