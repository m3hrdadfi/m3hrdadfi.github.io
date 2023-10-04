---
layout: page
title: Zabanshenas
description: is a solution for identifying the most likely language of a piece of written text.
img: assets/img/prj-zabanshenas-01.png
importance: 4
category: research
---

# Zabanshenas

A Transformer-based solution for identifying the most likely language of a written document/text. Zabanshenas is a Persian word that has two meanings:

- A person who studies linguistics.
- A way to identify the type of written language.


[In this repository](https://github.com/m3hrdadfi/zabanshenas), I will use another perspective in creating a language detection model using [Transformers](https://arxiv.org/abs/1706.03762). Nowadays, Transformers have played a massive role in Natural Language Processing fields. In short, Transformers uses an attention mechanism to boost the speed and extract a high level of information (abstraction).

There are plenty of ways, solutions, and packages to find the language of a written piece of text or document. All of them have their pros and cons. Some able to detect faster and support as many languages as possible. However, in this case, I intend to use Transformers to understand similar groups of languages and cover 235 languages thanks to [WiLI-2018](https://arxiv.org/abs/1801.07779) and the Transformer architecture.

This model can detect a written language in three different stages: paragraph, sentence, and subset of text between three and four tokens.
