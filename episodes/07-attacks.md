---
title: Attacks
teaching: 20
exercises: 10
---

::::::::::::::::::::::::::::::::::::::: objectives

- Understand the concept of adversarial attacks.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- How can models be intentionally mislead?

::::::::::::::::::::::::::::::::::::::::::::::::::

## Manipulation of models

It is important to be aware that models are susceptible to manipulation by targeted attacks. A model is susceptible to attack if it can be manipulated to produce an unexpected output. Currently most examples of models being mislead are theoretical - and often humourous - but this is likely to change as the stakes increase. These examples also demonstrate the fragility of models. It is not difficult to see how an algorithm-led system could reach an incorrect decision simply due to an unusual event.

## Adversarial attacks

One common method for attack is to alter input data to intentionally cause misclassification. Researchers at Google, for example, demonstrated that they could generate a sticker that could [trick a machine learning model](https://slate.com/technology/2018/01/google-researchers-tricked-an-a-i-into-thinking-a-banana-was-a-toaster.html) into confusing a picture of a banana with a toaster.

![](fig/banana.png){alt='Banana or toaster' width="800px"}

While the "adversarial patch" requires significant effort to fool the algorithm, researchers at OpenAI discovered that their image classification model could be fooled by nothing more than a pen and paper. They announced that a model that they had developed for classifying images would "respond to the same concept whether presented literally, symbolically, or conceptually. As a result, they demonstrated some [surprising results](https://www.theguardian.com/technology/2021/mar/08/typographic-attack-pen-paper-fool-ai-thinking-apple-ipod-clip) in the application of the model.

![](fig/poodle.png){alt='poodle' width="800px"}

![](fig/apple.png){alt='apple' width="800px"}

<!--

Data can be overlaid with targeted values that lead to misclassification.

https://www.science.org/doi/10.1126/science.aaw4399

https://arxiv.org/abs/1804.05296

Examples, and discussion.



https://twitter.com/MIT_CSAIL/status/1507754751995260931

https://slate.com/technology/2018/01/google-researchers-tricked-an-a-i-into-thinking-a-banana-was-a-toaster.html

https://www.theguardian.com/technology/2021/mar/08/typographic-attack-pen-paper-fool-ai-thinking-apple-ipod-clip


https://kde.mitre.org/blog/2018/10/28/is-this-a-wolf-understanding-bias-in-machine-learning/

https://arxiv.org/abs/1804.05296


TODO:

Look at 4 in https://arxiv.org/pdf/2012.05345.pdf



## Data injection

TODO:

Where models are continuously trained, there is risk that new training data might be intentionally injected in order to achieve a desired outcome.

-->



:::::::::::::::::::::::::::::::::::::::: keypoints

- Models are susceptible to manipulation.

::::::::::::::::::::::::::::::::::::::::::::::::::


