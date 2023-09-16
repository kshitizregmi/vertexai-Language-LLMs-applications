# Application of LLMs in Media

Using Large Language Models (LLMs) in various media and applications has become increasingly prevalent due to their ability to generate human-like text and facilitate natural language understanding.This rep contains some notable applications of LLMs in different media and industries.

## Overview

This repository houses a collection of Jupyter Notebook files that demonstrate the use of advanced language models for various text-related tasks. Whether you need to automatically generate article summaries, create catchy article titles, or generate hashtags for text content, this repo has you covered.

## About Model
The Googles VertexAI language model text-bison is a foundation model which is optimized for a variety of natural language tasks such as sentiment analysis, entity extraction, and content creation.

**Note: Each stable version of a model is available for six months after the release date of its subsequent version.**

A stable version of a model does not change and is available for six months after the release date of its subsequent version. For example, text-bison@001 is available for six months after the release date of text-bison@002. In this example, text-bison@001 becomes unavailable after the six months following the release date of text-bison@002. If you use a stable version that becomes unavailable, you need to switch to a newer available stable version. You can identify the version of a stable model by the three digit number that's appended to the model name. For example, text-bison@001 is version number one of the stable release of the Vertex AI Generative AI text model.

Google releases stable versions on a regular cadence. You can switch from one stable version to another as long as the other version is still available. When you move from one stable version to a different stable version, you need to run your tuning jobs again because there might be prompt, output, and other differences between the versions.

For More Visit: https://cloud.google.com/vertex-ai/docs/generative-ai/learn/model-versioning#stable-version

| Model name  | Description  | Model properties                   |
|-------------|--------------|-----------------------------------|
| text-bison  | Fine-tuned to follow natural language instructions and is suitable for a variety of language tasks, such as: Classification Sentiment Analysis Entity extraction Extractive Question Answering Summarization Re-writing text in a different style Ad copy generation Concept ideation | Max input tokens: 8192 Max output tokens: 1024 Training data: Up to Feb 2023 |


## Features

- **Article Summarization**: Implement an article summarizer using Large Language Models to generate concise and informative summaries of long articles.

- **Article Title Generation**: Generate compelling article titles with the help of text-bison Large Language Models, ensuring your content captures readers' attention.

- **Hashtag Generation**: Automatically generate relevant hashtags for your text content, simplifying the process of social media sharing and content tagging.

