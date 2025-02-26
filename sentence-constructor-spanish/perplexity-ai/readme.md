## Perplexity Pro

### Summary
I explored the o3-mini and Deepseek R1 models using Perplexity Pro version. Perplexity Pro uses their own model by default, but specific models can be chosen in user settings.

Existing sample prompt file has been changed and instructions modified to make experience a little bit more interactive:

I've change language level to CEFR level B1 in Spanish and instructed the model to only provide sentence in one of the following topics - everyday life, travel and tourism, food and dining, weather and seasons, socializing and hobbies, shopping, health and emergencies

In addition to that student has only 3 attempts to answer correctly, if correct answer is not provided, the model should provide the correct answer and move on to the next sentence

The student also earns 20 points for correct answer and 0 points for incorrect answer. Once 200 points thereshold is reached I've instructed the model to congratulate the student and end the session.

The model performed as expected allowing only 3 attempts and granting 20 points for correct answer and 0 points for incorrent answer.

I also tried to ask if model could provide the picture that would best describe the sentence provided but it did not show one - which was expected.

Additionally I tried to include 60 second timer and was presented with something like this when using R1 model:

Attempts left: 3
Time remaining: 60 seconds
Current points: 0

The model did not enforce 60 second timing.

### Additional useful links

https://www.perplexity.ai/hub/faq/prompting-tips-and-examples-on-perplexity

https://www.perplexity.ai/hub/technical-faq/what-model-does-perplexity-use-and-what-is-the-perplexity-model

It appears that Perplexity does not have any special prompting requirements (XML, markdown) to best understand context like other models.