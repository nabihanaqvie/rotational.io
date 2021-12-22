---
title: "Data Curation: A Whale of a Problem"
slug: "data-curation-baleen"
date: 2021-12-22T11:37:43-05:00
draft: false
image_webp: images/blog/whale.webp
image: images/blog/whale.jpg
author: Nabiha Naqvie
description: "This post delves into the recent developments in Artificial Intelligence (AI) and Natural Language Processing (NLP), and Baleen's approach towards it."
---

The world of AI has seen a rapid increase in its practical usage, where AI companies and startups raised $33 billion during 2020.¹ Many companies like Urbint are using AI and real-world data to predict and prevent incidents that threaten critical infrastructure, workers, the community, and the environment.² Similarly, DataRobot has the only AI Cloud platform with an AI-native strategic team to help its customers use and understand their data.³ The field of NLP has also seen a surge in its budget as 60% of NLP Tech Leader's budget grew by at least 10%, while 33% reported a 30% increase, and 15% reported more than doubled.⁴

Although this accelerated movement towards AI, NLP, and Machine Learning has added value to how we interact and preceive the world, it is also important to remember that Stephen Hawking warned us about this acceleration. Many of the machine learning models that are employed are built off of general datasets rather than custom datasets. Generative Pre-trained Transformer 3 (GPT-3) is an NLP model that is trained on a large text corpus to generate human-like text.⁵ It caused alot of excitement around human-like text production, where newspaper companies like The Guardian were publishing articles that were written by GPT-3.⁶ GPT-3 was considered the next big thing in the AI and the NLP world because its uses were unlimited: generating code, Regex, cloning websites, object-use case generation, creating charts and plots, playing games, identifying painting, producing quizes, meme maker etc.⁷ However, there was a turning point to this invention that sparked alot of controversy. Being trained on a general dataset, GPT-3 was definetely not perfect. When given the word "Muslim", GPT-3 would generate 60% of its sentences that including bombs and violence. Similarly, there was a greater association of negative words with "Black people". OpenAI addressed this issue by stating the following: "GPT-3, like all large language models trained on internet corpora, will generate stereotyped or prejudiced content.".⁸ The pitfalls of these megamodels on generic text is due to the data being too general, and therefore feeds toxic elements into the machine learning model. Github's Copilot is an example of AI that is trained on custom dataset. Copilot is run by OpenAI Codex that generates code faster. It works by understanding the given instructions and suggesting individual lines and whole functions instantly,⁹ and is trained on code respositories on Github.¹⁰ In order to properly utilize NLP, AI and deep learning, we need to produce quality models that contain quality data. This is were Baleen is filling in the gap.

Baleen is an automated ingestion service of RSS feeds to construct a corpus for NLP research. It takes Golang ingestion system that fetches RSS feeds and stores raw data into MongoDB. Baleen feeds data quality measurements with language statistics, such as words, vocab, rate of corpus growth, number of entities, etc.¹¹  With Baleen, our emphasis is to approach the NLP industry through generating and storing custom datasets to allow for better machine learning model.


***

Photo by [Art of Backpacking](https://flic.kr/p/8GAVjS) on [Flickr Commons](https://flic.kr/p/8GAVjS)

---
¹https://builtin.com/artificial-intelligence/ai-companies-roundup
²https://www.urbint.com/about
³https://www.datarobot.com/abo
⁴https://www.globenewswire.com/news-release/2021/09/21/2300838/0/en/Enterprise-Investments-in-Natural-Language-Processing-Surge-in-2021-and-Accuracy-Remains-the-Top-Concern-New-Research-Reveals.html
⁵https://en.wikipedia.org/wiki/GPT-3
⁶https://www.theguardian.com/commentisfree/2020/sep/08/robot-wrote-this-article-gpt-3
⁷https://www.educative.io/blog/top-uses-gpt-3-deep-learning
⁸https://onezero.medium.com/for-some-reason-im-covered-in-blood-gpt-3-contains-disturbing-bias-against-muslims-693d275552bf
⁹https://copilot.github.com/
¹⁰https://www.fast.ai/2021/07/19/copilot/
¹¹https://github.com/rotationalio/baleen

