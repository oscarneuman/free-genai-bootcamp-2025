## Meta AI

### Summary
I have tried identical prompt that used to test perplexity on meta ai platform and got pretty much identical experience/response.

Existing sample prompt file has been changed and instructions modified to make experience a little bit more interactive:

I've change language level to CEFR level B1 in Spanish and instructed the model to only provide sentence in one of the following topics - everyday life, travel and tourism, food and dining, weather and seasons, socializing and hobbies, shopping, health and emergencies

In addition to that student has only 3 attempts to answer correctly, if correct answer is not provided, the model should provide the correct answer and move on to the next sentence

The student also earns 20 points for correct answer and 0 points for incorrect answer. Once 200 points thereshold is reached I've instructed the model to congratulate the student and end the session.

Meta.ai at the time of testing is based on the 70 billion parameter version of Meta Llama 3.1 and performed pretty much identical to either o3-mini and Deepseek R1 models that I tried on Perplexity AI Pro version.

I also tried to ask if model could provide the picture that would best describe the sentence provided but it did not show one - which was expected.

### Additional useful links

Prompting Guide

https://www.llama.com/docs/how-to-guides/prompting/

The Model Card - provides essential information about LLaMA 3, including - model details, performance metrics, bias and limitations etc.

https://www.llama.com/docs/model-cards-and-prompt-formats/llama3_1/