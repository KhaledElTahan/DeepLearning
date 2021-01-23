# Project Proposal

Perhaps the most important delivery since all your term work depends on it. You are required to submit a **quality-document** containing the following requirements.

## Requirements

1. The proposed problem statement and its motivation.
2. Current state of the art accuracy for the proposed problem.
3. A short survey of available models and solutions for the proposed problem.
4. A detailed description of the model to be used from literature to build on. Also mention why you will use this particular model.
5. The proposed updates to the literature model. Also mention what benefit do you expect from this update and why you think it is a good idea to try it.
6. Write about how will you evaluate your results, what kind of evaluation metric you will use to compare your results, and what types of plots/graphs will be used to point out the comparison results.
7. A survey of available datasets for your course project problem. If your proposed problem is a reinforcement learning problem, then provide a survey of available environments that your model can work on.
8. A detailed description of the dataset (or environment for reinforcement learning) to be used. Also mention why will you use this particular dataset.
9. Your graduation project brief problem statement, even if it is not the same as the proposed course problem statement.
10. If your proposal is related to your graduation project, point out the differences that will
be made between this problem statement and your graduation project problem statement.
11. Mention all available online resources/papers you will collect during the survey.

## Guidelines for choosing the problem

Those guidelines are not mandatory, however, they might help you avoiding struggles past students faced.

### 1. Resources

The following are great hubs to search for a paper with code.

* [Papers with Code SOTA](https://paperswithcode.com/sota)
* [Made with ML](https://madewithml.com/)

### 2. Problem Domain

I highly recommend you to avoid any problem domain that works with videos unless you're sure the training time is feasible.

### 3. Code

I recommend you to find an already implemented paper and work on top of it, but the implementation code should follow the next guidelines for smooth future updates.

* Framework: Choose recent code with recent framework, for example tensorflow 2.x or pytorch.
* Weights: Make sure the pretrained weights are already provided.

### 4. Dataset

Make sure the dataset is not huge to avoid problems for downloading, preprocessing, loading on memory (RAM), and training time.

### 5. Training Resources & Time

Most common problem is that you cannot train the network due to the lack of resources to meet the required training time, make sure you have this in mind while selecting your problem.

## Selected Proposals

The following are selected proposals from past years, I highly recommend you to take a look on them before writing your proposal.

* [Text to Image](assets/selected_proposals/text_to_image.pdf)
* [Snake Game](assets/selected_proposals/snake_game.pdf)
* [Moving Object Detection](assets/selected_proposals/moving_object_detection.pdf)
* [Food Image Recognition](assets/selected_proposals/food_image_recognition.pdf)
* [Image Colorization](assets/selected_proposals/image_colorization.pdf)
* [Artistic Style Transfer For Videos](assets/selected_proposals/style_transfer.pdf)
* [Anomaly detection using AEs](assets/selected_proposals/anomaly_detection.pdf)

**Note**: those proposals might have been made with different requirements, just because any of them doesn't meet any of our requirements doesn't give you the ability to do the same.

## FAQs

### 1. What happens next?

I will review your proposal and check that it meets each individual specified requirement and whether accept, accept with updates or reject it.

The proposal update phase will be used to update the proposal incase of rejection or updates request.

### 2. How this phase is graded?

* Each individual specified requirement has a grade.
* Clear amount of effort done.
* Overall proposal document quality.
* The readability of the proposal.

### 3. What is not acceptable in this phase?

The following are some examples of unacceptable work in proposals:

* Just copying one or two papers into the proposal and sort the proposal in a different order.
* Having sentences like "We achieved the state of the art results", which shows clearly that you didn't write this proposal specifically to me.
* Some proposals assume that the reader is aware of all the world terminology, sentences like "We will use LR image" and I'm left to figure out what is LR.
* Some proposals don't state clearly the basemodel or any model, sentences like "we will use sequence to sequence". How am I supposed to know what type of model you will use from the sequence to sequence family?

You need to be precise, discrete, and organized.

### 4. Can I use the same problem proposed in selected proposals?

Unless you provide a major update I will most probably reject your proposal.
