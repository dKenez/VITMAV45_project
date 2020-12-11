# VITMAV45_project
### Team members:
Béres Bálint
Drexler Kristóf
Drexler Konrád

### Summary:
This is a project were we used deep learning to train a model to output answers to input sentences.

This model was trained on 5 different subreddits from the website Reddit. This means there was not garantee the trained model will have any chance of outputting anything resembeling the english language, however thankfully the model did acquire some notion of how to properly structure sentences.

Limiting factor was computing power and RAM, as we used the online google colab interface. We circumvented the RAM issue by using generators for the datasets which were used to train the model.

There are many paths forward, which can result in an improved model, but the current results are acceptable for now.

### How to use:
The notebook is divided up into sections detailing our proccess of training the model. Towards the end of the file there is a cell which accepts inputs from the user and feeds that to the model, which outputs a sentence.
