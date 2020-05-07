# Priors in Academia - Epistemological Space in Psychology Literature

Final Project for [Computational Content Analysis](https://github.com/Computational-Content-Analysis-2020), Spring 2020, The University of Chicago

Nak Won Rim

# Contexts

Although grouped under a single domain name, psychological researches are amazingly broad in their variety. Psychologists from different subsections and different schools of thought often have highly different opinions on controversial topics in the field. While such diversity within the discipline is a sign of a healthy academic environment, it could potentially lead to an issue: cognitive biases in acknowledging others’ works that stems from these differences.

As such, the purpose of this project is to understand the relationship between researchers’ preferences/opinions (or cognitive bias toward some issues) and the works they produce in academia. Specifically, my main question could be phrased as:

* Is there a clustering (whether in the topic space or word embedded vector space) of psychological articles in the epistemological space of psychology literature? In other words, can we locate the "fracture" between the psychological articles and group sub-sections of psychology based on text data? If so, are these clusters related to the opinions on psychology that researchers that contribute to each cluster share?

# Data

To address this issue, I will do content analysis using abstracts from psychological journals, and try to link it to a survey conducted on psychologists.

## Survey

I am going to use survey data from [Academic Priors Project](http://academic-priors.herokuapp.com/). The researchers surveyed more than 7,000 psychologists and people from related disciplines to get their views on 16 controversial topics in psychology. For example, one question they asked was to rate how strongly the participants agreed/disagreed on the following statement:

> There are some patterns in nature that we will never understand, given the limitations of our minds.

## Texts

The text data I am going to use is the abstracts collected from psychology articles. I am planning on using a relatively small corpus for this project (although still massive – for instance, even if I limit the articles to those published in 2018 and labeled “psychology” on Web of Science, I would still be dealing with more than 35,000 articles), and grow the corpus size if these get connected to publications. I am still in the process of data collection. Please note that even if I have the full data, the corpus could not be uploaded here since it will be impossible to upload the data to a public repository for copyright reasons.
