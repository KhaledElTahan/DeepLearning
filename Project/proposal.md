# Project Proposal

Perhaps the most important delivery since all your term work depends on it. You are required to submit a **quality-document** containing the following requirements.

## Proposal Document Requirements

1. The proposed problem statement and its motivation. Use figures and plots to explan your problem statement.
2. Input/Output examples that explain the problem statement, also use figures and plots to illustrates those examples.
3. A survey of available evaluation metrics and tools for this problem.
4. Current state of the art results (results of correct evaluation metrics, for example accuracy in some class classification problems) for the proposed problem.
5. A survey of available datasets for your course project problem. If your proposed problem is a reinforcement learning problem, then provide a survey of available environments that your model can work on. This survey should include, examples of the dataset (In figures if possible, I want to see an input and an output), a website link for the dataset, the dataset storage size (in MBs or GBs), the dataset examples size (number of examples in training/validation/testing splits), and any other important information.
6. A detailed description of the dataset (or environment for reinforcement learning) to be used. Also mention why will you use this particular dataset.
7. The selected dataset shouldn't exceed 20 GB (requirement, but 15GB recommended), if otherwise, please explain why do you find using this dataset is feasible.
8. A survey of available models and solutions for the proposed problem. This survey should include, figures and plots to explain each model, reference paper for each model, public repository code link, information about frameworks used in the code, information about available weights and model zoo, information about training resources required for them if available, results of each model and comparison between them in a table, and any other important information.
9. A detailed description of the model to be used from literature to build on. Also mention why you will use this particular model.
10. The source code URL for the selected baseline model. It should be written in a recent framework, as Tensorflow 2.x or TF.Keras or PyTorch and in few files (20 code files or less). If there's no available source code, or the source code doesn't use the mentioned frameworks, please jusitfy how will you approach your project without them.
11. The model weights or model zoo URL. If there're no model weights, please jusitfy how will you approach your project without them.
12. The proposed updates to the literature model. Also mention what benefit do you expect from this update and why you think it is a good idea to try it.
13. Write in details about how you will evaluate your results, what kind of evaluation metric you will use to compare your results, and what types of plots/graphs will be used to point out the comparison results.
14. **Your graduation project (or thesis) brief problem statement, even if it is not the same as the proposed course problem statement.**
15. **If your proposal is related to your graduation project (or thesis), point out the differences that will be made between this problem statement and your graduation project (thesis) problem statement.**
16. Mention all available online resources/papers you will collect during the survey.
17. Each team member contribution. You should state only the contribution in the technical work, so writing the document for example shouldn't be included.

## Deliverables

1. A quality-document containing the requirements.

## Guidelines for choosing the problem

Those guidelines are not mandatory, however, they might help you avoiding struggles past students faced.

### 1. Resources

The following are great hubs to search for a paper with code.

* [Papers with Code SOTA](https://paperswithcode.com/sota)
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [Made with ML](https://madewithml.com/)

### 2. Problem Domain

I highly recommend you to avoid any problem domain that works with videos unless you're sure the training time is feasible.

### 3. Dataset

Make sure the dataset is not huge to avoid problems for downloading, preprocessing, loading on memory (RAM), and training time.

### 4. Training Resources & Time

Most common problem is that you cannot train the network due to the lack of resources to meet the required training time, make sure you have this in mind while selecting your problem.

You need to ask your self the following questions:

1. Can I train the model on a local machine?
2. Can I train the model on Google Colab?
3. Can I train the model on other cloud service?

If you have an access to credit card, then [this tutorial: 'Using Azure Free 200$ Credit for Deep Learning'](https://youtu.be/EFVU8EnibXw) might be beneficial to you.

## Selected Proposals

The following are selected proposals from past years, I highly recommend you to take a look on them before writing your proposal.

* [Text to Image](assets/selected_proposals/text_to_image.pdf)
* [Snake Game](assets/selected_proposals/snake_game.pdf)
* [Moving Object Detection](assets/selected_proposals/moving_object_detection.pdf)
* [Food Image Recognition](assets/selected_proposals/food_image_recognition.pdf)
* [Image Colorization](assets/selected_proposals/image_colorization.pdf)
* [Artistic Style Transfer For Videos](assets/selected_proposals/style_transfer.pdf)
* [Anomaly detection using AEs](assets/selected_proposals/anomaly_detection.pdf)

**Note**: those proposals might have been made under different requirements, just because any of them doesn't meet any of our requirements doesn't give you the ability to do the same.

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

### 4. Can I use the same problem proposed in selected proposals or past project website?

Unless you provide a major update I will most probably reject your proposal.

### 5. Can I use the same problem statement I use in my graduation project (or thesis)?

You can use the same domain, but you have to tackle a different issue other than the one you're investigating in your graduation project (thesis).
