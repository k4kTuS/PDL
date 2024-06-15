# Practical Deep Learning Course Submissions
This repository contains code created during a FIT CTU course on Practical Deep Learning. Two student competitions took place during the course, focused on NLP and CV.

## NLP Competition - Text regression
### Description

The task of the competition was to predict the difficulty of given questions from various scientific topics. The dataset was generated using ChatGPT-3.5. It contained 6500 entries in the training set and 2000 entries in the test set. The test set submissions were evaluated on Mean Absolute Error (MAE).

**Dataset structure:**
- id - id of the question
- question - question text
- category - question TOPIC
- difficulty - rating from 1 to 10 (training set)

### Final solution
Implementaion available in `nlp-competition.ipynb` jupyter notebook. 
- 4th place out of 20
- MAE: 1.10933

## CV Competition - Image classification
### Description

The task of the competition was to predict the artist style of generated images. The styles were represented by one of the following artists: Vincent van Gogh, Salvador Dali, Claude Monet, Rembrandt Harmenszoon van Rijn, Pablo Picasso, Andy Warhol. The dataset was generated with Stable Diffusion model and contained 6500 entries for the training set and 2000 entries for the test set. Accuracy was used to evaluated the test submissions.

**Dataset structure:**
- image_id - name of the image in images/ directory
- label - artist's name (only available in train data)

### Final solution
Implementaion available in `cv-competition.ipynb` jupyter notebook. 
- 7th place out of 21
- Accuracy: 0.83733
