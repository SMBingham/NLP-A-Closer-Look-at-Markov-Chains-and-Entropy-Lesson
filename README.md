# Lesson README
## NLP: A Closer Look at Markov Chains and Entropy 

Written by Shannon Binghan


## Summary
With this lesson, I lead the learner(s) to deeper intuitions about concepts that are fundamental to Natural Language Processing (NLP):
- information processing framed as a communication problem
- the rationale for the incorporation of probability and statistics in information theory
- Markov chain processing
- entropy as a measure of the uncertainty of a message


## Objective
The primary objective of the lesson is for learner to gain/strengthen insights about:
- how and why probability and statistics underlie modern information theory
- how Markov chains are used in word prediction
- the development of the theory of entropy from word prediction experiments.


## Outline
This lesson was developed in accordance with constructionist principles and incorporates a combination of direct instruction and experiential learning.  In terms of a 5E lesson model, the lesson steps followed this flow:
  - Engage (slides)
      - Share motivation for lesson
      - Connect the lesson to prior learning
  - Explore/Explain (experiments template)
      - Participate in experiments similar to those used by Claude Shannon to develop his theories of information and entropy
      - As part of the experiments, encourage learners to share their thinking about their letter predictions
      - At the conclusion of each experiment, bring attention to the data collected during the experiment that Claude Shannon used
  - Elaborate (Jupyter notebook)
      - Walk through and execute the letter prediction code.  
  - Evaluate (slides)
      - Provide opportunity for further discussion and questions.
      - Connect key concepts back to prior learning.


## Lesson Deliverables
- Git repository located on my personal GitHub and on General Assembly's GitHub Enterprise.  The repository:
    - README markdown file that explains the lesson:
        - summary
        - outline
        - objective
    - PDF version of the lesson slides
    - PDF version of the experiment templates
    - Jupyter python notebook containing the code to build a Markov chain machine with order 1
    - text file containing input data for python code
    - `.gitignore`  file
    

## Resources
Primary resources used to develop the lesson content:

C. E. Shannon, "A Mathematical Theory of Communication," Bell System Technical Journal, v. 27, pp. 379-423, 623-656, July, October,  1948.

C. E. Shannon, "Prediction and Entropy of Printed English," Bell System Technical Journal, v. 30, pp. 47-51, 1951.

Jurafsky, Daniel, and James H. Martin. 2009. Speech and Language Processing: An Introduction to Natural Language Processing, Speech Recognition, and Computational Linguistics. 2nd edition. Prentice-Hall.

[Kahn Academy]. Information Entropy [Video File]. Retrieved from https://www.khanacademy.org/computing/computer-science/informationtheory/moderninfotheory/v/information-entropy


