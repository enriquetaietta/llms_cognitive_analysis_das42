# DASS-42 and LLMs Psychometric Analysis Repository

## Overview

This repository is dedicated to the exploration and analysis of psychological prompts, primarily focusing on the DASS-42 test, using state-of-the-art Language Models (LLMs). The intersection of natural language processing and psychological assessments provides a unique opportunity to gain deep insights into cognitive and emotional aspects.

## What is DASS-42?

The DASS-42 is a self-report scale comprising 42 items, meticulously designed to asses negative emotional states, specifically targeting depression, anxiety, and stress. In clinical settings, the DASS-42 plays a pivotal role in pinpointing the locus of emotional disturbances, contributing to a comprehensive clinical assessment.

## About LLMs

Language Models, especially Large Language Models (LLMs), such as GPT-3.5, have demonstrated remarkable capabilities in understanding and generating human-like text. Leveraging these models in psychological research allows for the analysis of nuanced linguistic patterns, potentially uncovering hidden insights within the responses to DASS-42 prompts.

## Repository Contents

- **Prompts:** We've identified 5 common 'events' a student might encounter, providing both positive and negative versions for each event. To delve deeper into potential biases, we've also diversified the prompts based on gender. Join us as we explore the nuances of student experiences in this introductory phase of data gathering.
We've tried to investigate the responses on:
1. Comprehensive Examinations
2. Research Pressure
3. Publish in peer-reviewed Journals
4. Teaching Responsibilities
5. Advisor Relationships


- **Responses:** The responses are in the format name csv__openai-**#gender#**-event-**#eventnumber#**-**#eventtype#**-**#outputformat#**
    -   For each case we produced 3 different format types: 
        1. **Base**: One row for a ChatGPT OpenAI call ID and all the numeric responses to the test
        2. **FMN**: A format for the Forma-Mentis Network. 4 columns with ID, Question number, response value, sentence
        3. **Sentence**: One for each call, with Id and all the sentences

