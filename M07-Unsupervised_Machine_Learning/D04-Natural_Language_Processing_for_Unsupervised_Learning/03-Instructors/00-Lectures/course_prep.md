# NLP

This course introduces the processing of natural language.
You should start the lesson with a general introduction to what specificities come with analysing language as data, for example:
* language is ambiguous
* written language and spoken language are not always aligned
* language is not numerical
...

A very useful tool for text processing is regular expressions, a great interface to create regular expression is [regexr](https://regexr.com/), take some time to present it to the students.

You may have some time left after the exercises to work on the projects with the students

# Lectures

## 01-Introduction_to_NLP - 60 min

This lectures introduces different techniques for handling language as data, it is important that the students understand that:
* language as a structure, words do not come in a random order, a sum of words does not necessarily give the same meaning depending on the order
* as data scientists you'll have to define a unit of language on which to base your analysis
    * character level
    * unigrams (1 word)
    * bigrams (groups of 2 words) etc...
    * sentence level
    * ...

The goal of processing text is ultimately to transform the text data into numerical data.

You will present three techniques:
* parse trees
* term frequency
* TfIdf

## 02-Code_NLP - 30 min

This demo will show the students how to transform a corpus of text into a numerical dataset where each document (think sentence in a text, or text in a group of text, or chapter in a novel)

The students will learn how to use spacy in order to preprocess text (remove punctuation, remove stopwords, collapse words with the same root etc...)

Then they will learn how to use sklearn in order to transform text data into numerical data (this will introduce a new type of object, the sparse matrices, which are not easy to visualize because their dense form will not necessarily fit into memory)

Finally they will learn how to visualize wordclouds and parse trees

# Exercises

## 01-Learn_about_Obi_Wan_Kenobi - 60 min

This exercise will let the students play around with text processing, wordclouds and TfIdf