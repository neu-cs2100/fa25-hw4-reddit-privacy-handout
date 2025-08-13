# Homework 4

## Learning Outcomes

- Parsing JSON data
- Visualizing data
- Sorting, filtering, and joining Pandas dataframes
- Privacy implications of pushing usernames and passwords to GitHub

## Overview

- Code using News API, which requires a key
- hide the key (don't push it to GitHub)
- discuss passwords people have accidentally put in GitHub code, and why ChatGPT could now output them

## Ethics and Privacy

Please fill out this table about API keys used in code. (Some parts are already answered for you, and you may look at Lab 1 for help):

| Question | Answer |
| -------- | ------ |
| What type of information is shared? | API key |
| Who is the subject of the information? | The programmer / code that's making API calls |
| Who is the sender of the information? | The programmer |
| Who are the potential recipients of the information? | Intended recipient: the API server<br />Unintended recipient(s): YOUR ANSWER HERE |
| What principles govern the collection and transmission of the information? | YOUR ANSWER HERE |

You may go back and edit your answers in the table as you answer these questions:
1. As we saw in Lab 5, large language models (LLMs) are trained on large parts of the internet. Are any popular LLMs trained on open source code like GitHub?
2. If a programmer accidentally pushes their API key to GitHub, who are at least two potential unintended recipients of this data?
3. How might we design our code to minimize the number of unintended recipients of that information? How might we redesign APIs to minimize the number of unintended recipients?
