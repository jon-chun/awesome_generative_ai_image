# ThePhish

<div>
  <p align="center">
    <img src="pictures/logo.png" width="800"> 
  </p>
</div>

ThePhish is an automated phishing email analysis tool based on [TheHive](https://github.com/TheHive-Project/TheHive), [Cortex](https://github.com/TheHive-Project/Cortex/) and [MISP](https://github.com/MISP/MISP). It is a web application written in Python 3 and based on Flask that automates the entire analysis process starting from the extraction of the observables from the header and the body of an email to the elaboration of a verdict which is final in most cases. In addition, it allows the analyst to intervene in the analysis process and obtain further details on the email being analyzed if necessary. In order to interact with TheHive and Cortex, it uses [TheHive4py](https://github.com/TheHive-Project/TheHive4py) and [Cortex4py](https://github.com/TheHive-Project/Cortex4py), which are the Python API clients that allow using the REST APIs made available by TheHive and Cortex respectively.

<!-->
![OS](https://img.shields.io/badge/OS-Linux-red?style=flat&logo=linux)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python%203.8-1f425f.svg?logo=python)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-available-green.svg?style=flat&logo=docker)](https://github.com/emalderson/ThePhish/tree/master/docker)
[![Maintenance](https://img.shields.io/badge/Maintained-yes-green.svg)](https://github.com/emalderson/ThePhish)
[![GitHub](https://img.shields.io/github/license/emalderson/ThePhish)](https://github.com/emalderson/ThePhish/blob/master/LICENSE)
[![Documentation](https://img.shields.io/badge/Documentation-complete-green.svg?style=flat)](https://github.com/emalderson/ThePhish)
-->

## Contents
&nbsp;

* [**Overview**](#overview)

&nbsp;

* [**Media**](#media)

&nbsp;

* **Technical Resources**
  * Models
	+ [GPT3.5](#gpt35)
	+ [ChatGPT](#chatgpt)
	+ [Jasper](#jasper)
	+ [Kalteb](#kalteb)
  * Prompt Engineering
    + [ChatGPT](#prompt-chatgpt)
	+ [GPT 3](#prompt-gpt3)
  * Security
	+ [Jailbreaks](#jailbreaks)
	+ [Redteam](#redteam)

&nbsp;

* **Research**
  * Coming...

&nbsp;

* **Ethics**
  * eXplainable AI 
    + [XAI](#xai)
  * Fairness, Accuracy, Transparency & Explainability
    + [FATE](#fate)

&nbsp;

* **Education**
  * Plagiarism
    + Detection Characteristics
	  + [False Confidence]()
	  + [Citations]()
	  + [Limited Knowledge](https://news.ycombinator.com/item?id=34242193)
    + Detectors - Free
	  + [OpenAI Detector](#openai-detector)
	  + [RoBERTa Detector](#roberta-detector)
	  + [GPT2 GLTR](http://gltr.io/dist/index.html)
	  + [GPT2 Zero](#gpt2-zero)
	  + [OpenAI Watermarks](#plagiarism-detection)
	+ Detectors - Paid
	  + [Originality.ai](#originality-ai)
	  + [HanditIn](#handitin)
	+ Evasion
	  + [Prompt Engineering](#evasion-prompt)
	  + [Selective Edits](#evasion-edits)
	  + [Summarization](#evasion-summary)
	  + [Translation Loops](#evasion-translations)
	  + [Others](#evasion-other)
  * Counter Measures & Adaptations
    + [one]()
	+ [two]()
  * University/College Policies
	  + [Georgetown](#georgetown)

* **Other Resources**
  * Awesome Generative AI
    + [steven2358](https://github.com/steven2358/awesome-generative-ai)

  * Etc

* **Notes**
  * [Contributing Links](#contribution)
  * [License](#license)
  * [Academic publications](#publications)
  * [About Us](#about-us)


# Overview

The following diagram shows how ThePhish works at high-level:

[Back to Contents](#contents)

&nbsp;

# Media

* [How to Use ChatGPT and Still Be a Good Person: It’s a turning point for artificial intelligence, and we need to take advantage of these tools without causing harm to ourselves or others.](https://www.nytimes.com/2022/12/21/technology/personaltech/how-to-use-chatgpt-ethically.html) by Brian X. Chen, The New York Times (21 Dec 2022)

* [AI and the Future of Undergraduate Writing](https://www.chronicle.com/article/ai-and-the-future-of-undergraduate-writing) by Beth McMurtrie, The Chronicle of Higher Education (13 Dec 2022)

* [The College Essay is Dead: Nobody is prepared for how AI will transform academia.](https://www.theatlantic.com/technology/archive/2022/12/chatgpt-ai-writing-college-student-essays/672371/) by Stephen Marche, The Atlantic (6 Dec 2022)

[Back to Contents](#contents)

&nbsp;

# Models
## GPT35

* [OpenAI GPT3x](https://beta.openai.com/docs/model-index-for-researchers)

## ChatGPT


## Jasper

## Kalteb

# Prompt Engineering

## Prompt ChatGPT

* [f/Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
* [DAIR-AI Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
* [ChatGPT Prompt Book](https://docs.google.com/presentation/d/17b_ocq-GL5lhV_bYSShzUgxL02mtWDoiw9xEroJ5m3Q/edit#slide=id.g1b87a629f77_0_11)

* [LearnGPT Examples](https://www.learngpt.com/)

## Prompt GPT3

* [OpenAI Cookbook](https://github.com/openai/openai-cookbook)

# Security

## Jailbreaks

* [alignedai/ChatGPT-Prompt-Evaluator](https://github.com/alignedai/chatgpt-prompt-evaluator)

## Red Team

# Research

# Ethics
## XAI

## FATE

* [Stanford HELM](https://hai.stanford.edu/news/language-models-are-changing-ai-we-need-understand-them)

# Education

## Plagiarism

### Detectors-Free

* [OpenAI Detector](https://huggingface.co/openai-detector/)

* [RoBERTa Detector](https://huggingface.co/roberta-base-openai-detector) and [repo](https://github.com/openai/gpt-2-output-dataset/tree/master/detector)

* [ChatGPT Self-Detection](https://blog.ouseful.info/2022/12/12/can-chatgpt-detect-gpt3-generated-texts/)

* [GPT2 GLTR](http://gltr.io/dist/index.html)

* [GPT2 Zero](https://etedward-gptzero-main-zqgfwb.streamlit.app/)

* [OpenAI Watermarks](https://scottaaronson.blog/?p=6823)

### Detectors-Paid

* [Originality.ai](https://metaroids.com/feature/the-future-of-chatgpt-content-how-ai-detection-tools-are-shaping-the-landscape/)

* [HanditIn](#handitin)

## Evasion

* [Prompt Engineering]()

* [Selective Edits](#evasion-edits)

* [Summarization](#evasion-summary)

* [Translation Loops](#evasion-translations)

* [Others](#evasion-other)

## Adaptations

* [Plagiarism and ChatGPT Get ready to interrogate students about their AI-enabled answers.](https://reason.com/volokh/2022/12/28/plagiarism-and-chatgpt/) by Josh Blackman, The Volokh Conspiracy (28 Dec 2022)

* [When AI tools like ChatGPT can write, how should we teach writing?](https://withoutbullshit.com/blog/when-ai-tools-like-chatgpt-can-write-how-should-we-teach-writing) by Academic, WithoutBullshit.com (15 Dec 2022)

# University/College Policies

* [Today, I turned in the first plagiarist I’ve caught using A.I. software to write her work, and I thought some people might be curious about the details.](https://www.facebook.com/title17/posts/pfbid0DSWaYQVwJxcgSGosS88h7kZn6dA7bmw5ziuRQ5br2JMJcAHCi5Up7EJbJKdgwEZwl) by Darren Hudson Hick, Facebook (15 Dec 2022)

* [Universities like Georgetown are attempting to detect cheating with ChatGPT. They will fail.](https://withoutbullshit.com/blog/universities-like-georgetown-are-attempting-to-detect-cheating-with-chatgpt-they-will-fail) by Academic, WithoutBullshit.com (22 Dec 2022)

# Regulation

* [3 Ways to Tame ChatGPT: Governments around the world are pushing AI regulation that has nothing to say about generative models. That could be dangerous.](https://www.wired.com/story/chatgpt-generative-ai-regulation-policy/) by Meeri Haataja, Wired (15 Dec 2022)
# Other Resources

## Awesome Generative AI

* [AI Text Generators: Sources to Stimulate Discussion](https://docs.google.com/document/d/1V1drRG1XlWTBrEwgGqd-cCySUB12JrcoamB5i16-Ezw/edit#heading=h.y7vlxxluoxbv) by Anna Mills

* [steven2358/awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai)

## Related Fields

* [Stance Detection](https://paperreading.club/page?id=147735)


# Notes

* [Contributing Links](#contribution)
* [License](#license)
* [Academic publications](#publications)
* [About Us](#about-us)
