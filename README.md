# What are the most popular data science questions?

## Scenario
Data science is an increasingly popular subject for employers and students. If we were to create data science content (such as guides, online articles, or videos) which topics are the best to focus on?

## Approach
In this case 'best' can mean many different things, so this question will be approached by looking to answer the following question: "*What is it that people want to learn about in data science?*", i.e. what are the most popular questions? 

To do this the **'tags' (i.e. topics)** have been extracted from all the questions on a popular [data science Q&A website](https://datascience.stackexchange.com/).

## Questions

1. What is the most used tag?
2. What is the most viewed tag?
3. What is the highest scored tag?
4. What are the relations between tags:
    1. How many tags are there per question?
    2. Which top 20 tags are not present across all metrics?
    3. Which pairs of tags are commonly used together (by number)?
    4. Which pairs of tags are commonly used together (by percentage)?
    5. Findings
5. Is deep learning just a fad?
6. How many questions are asked about Python vs. R?

The full analysis can be found in the [following notebook](https://nbviewer.jupyter.org/github/vivek-kotecha/popular-data-science-topics/blob/main/popular_data_science_qs.ipynb).

## Key Results

1. Topics related to Deep Learning are the most used, viewed, and commented tags on the Data Science Q&A website.

2. Deep learning is consistently a popular topic making up just under 50% of all questions asked.

3. Python has been the most popular language on the Q&A website since 2016.

## Selected output

Q4d. Which pairs of tags are commonly used together (by percentage)?

![percentage_heatmap](/output/tag_percent_occurence.png)

5. Is deep learning just a fad?

![questions_by_year](/output/questions_yearly.png)

6. How many questions are asked about Python vs. R?

![r_vs_python](/output/r_vs_python.png)

## Installation

First clone the repository in a local folder
```
git clone https://github.com/vivek-kotecha/popular-data-science-topics.git
```
then run the scripts from the terminal with

```
python {filename}.py
```
or
```
python3 {filename}.py
```

## Dependencies

A comprehensive list of current dependencies include the following libraries
```
Pandas (data manipulation)
Numpy (scientific computing)
Matplotlib (plotting)
Seaborn (plotting)
```
