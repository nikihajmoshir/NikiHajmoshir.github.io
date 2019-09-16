---
layout: post
title: Tweet Summarization using Tf-IDF and Word2Vec
---

So, I am working on a side project which basically is about summarizing tweets using tf-idf and word2Vec.

We know for a fact, the in a sentence named entities(orgnisations, names, locations, etc) provide the majority of the information. Lets say we collect tweets on a specific topic using  a specific hashtag. Now from our tweet corpus, I want to find out the mean tf-idf score of every word in the corpus. Once I have that the idea is to find out the Named Entities of every tweet using NER(Named Entity Recognition) and assign a score to every tweet by just adding up the mean tf-idf scores of all the entities in the sentence.

Then I plan on using Word2Vec to find out similar tweets and only keeping the ones with higher score than the other ones. So in the end I am left with tweets which convey the most useful and unique information.

Will keep updating on the project.
