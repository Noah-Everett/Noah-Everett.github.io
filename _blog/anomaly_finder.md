---
layout: archive
title: ""
permalink: /ideasblog/anomaly_finder/
author_profile: true
redirect_from:
  - /anomalyfinder/
---

<h1>Using LLMs to Find Solutions to Unsolved Anomalies</h1>
<p style="margin: 0;">Originally written: Oct 29, 2024 by Noah Everett as part of the Ideas Blog</p>

## Introduction

<img src="/images/anomalous_search.jpeg" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
Unsolved anomalies in science and mathematics have long been a source of fascination and frustration for researchers. 
These anomalies represent gaps in our understanding of the natural world, often defying explanation despite numerous attempts. 
Traditional methods of solving these anomalies involve human intuition, creativity, and rigorous mathematical reasoning.
However, the rise of large language models (LLMs) in artificial intelligence presents a new opportunity to tackle these challenges.

I propose that there may already exist solutions to unsolved anomalies which have not been linked to the anomalies themselves. 
These solutions may be buried in the vast amounts of text and data available on the internet, scientific literature, and other sources. 
By leveraging LLMs we can search for and extract these hidden solutions, potentially shedding light on long-standing mysteries.

## Introduction to LLMs

If you have been living under a rock for the past year or so, you might not have heard of large language models (LLMs).
These models, such as ChatGPT, BERT, Claude, etc. have revolutionized natural language processing tasks by learning to generate human-like text.
They are trained on massive amounts of text data and can generate coherent and contextually relevant text responses to a wide range of prompts.
We call the input to these models a "prompt" and the output a "response".
An example of this is "What is the capital of France?" to which the model might respond "Paris".
For us this may look something like "What caused the MiniBooNE anomaly?"; then it is our goal to have the model respond with a coherent and potentially correct answer.

The vast recent increases in the ability of these models is incredible.
The majority of these models use a transformer architecture [[Vaswani, et al., 2017](https://arxiv.org/abs/1706.03762)], which is a type of neural network that is particularly good at processing sequential data.
The transformer architecture has been shown to be highly effective at a wide range of natural language processing tasks, including text generation, translation, summarization, and question-answering.
These models are typically trained on large-scale datasets (roughly speeking the entire internet) to learn the statistical patterns in the data and generate human-like text.

## Overview of the Approach

The approach involves training an LLM on a diverse corpus of text data, including scientific papers, books, websites, and other sources.
I hope that pre-existing models/architectures like those from OpenAI, Meta, and Anthropic (among many others) will be capable of this task given the right setup.


Image credits: DALL-E by OpenAI