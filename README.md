# Course Homepage for CS 480/680
Fall 2024, University of Waterloo

### :bulb: Lectures
Lecture slides and video lectures (recorded offline) will be linked here. Please note that the topics and schedule for all future lectures are tentative.

The suggested readings make use of the following abbreviations to refer to textbook sources:

**UML**: [Understanding Machine Leaning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/). *Shai Shalev-Schwartz and Shai Ben-David*.

**ESL**: [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/). *Trevor Hastie, Robert Tibshirani, and Jerome Friedman*.

**ISL**: [Introduction to Statistical Learning](https://www.statlearning.com/). *Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani.*

**PML**: [Probabilistic Machine Learning](https://probml.github.io/pml-book/book1.html). *Kevin P. Murphy*

**PRML**: [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/). *Christopher M. Bishop*

| LECTURE    | DATE | TITLE             | MATERIALS      |  SUPPLEMENTARY READINGS |
| ---------- |---|----------------- |--------------- | --------- |
| 0          | 05/09/2024 | Logistics & Introduction     | [Slides](lectures/00_introduction.pdf)<br>[Video Lecture](https://youtu.be/UpYhHUnzFDQ) | N/A       |
| 1          | 10/09/2024 | Halfspaces & The Perceptron Algorithm     | [Slides](lectures/01_halfspaces_perceptron.pdf)<br>[Video Lecture](https://youtu.be/lpgRhhzjncA?si=PO6lRbo3VUIoPW3l)<br>[Perceptron Video](https://youtu.be/Bf6qu2tb8TE?si=kNGngvLevms1EG-t) | UML Section 9.1<br>ESL Section 4.5<br>[Yaoliang Yu's Lecture Notes](https://cs.uwaterloo.ca/~y328yu/mycourses/480-2022f/480-note-perceptron.pdf)<br>[Varun Kanade's Lecture Notes](https://www.cs.ox.ac.uk/people/varun.kanade/teaching/AML-HT2017/lectures/mistakebound-online.pdf) |
| 2          | 12/09/2024 | Linear Regression & Loss Function Design | [Slides](lectures/02_linear_regression.pdf)<br>[Video Lecture](https://youtu.be/pJ05fO5CTvw?si=W8mqJ3jYPB_CsEOm)             | UML Section 9.2, 11.2<br>ESL Section 3.2, 3.4, 7.10<br>ISL Sections 3.1-3.2, 5.1, 6.2<br>[Gautam Kamath's video on Rewriting Loss Functions](https://youtu.be/oR4NqeaCi34?si=_4r_NbpxT76LbmmD&t=1998)
| 3          | 17/09/2024 | Maximum Likelihood Estimation & Information | [Slides](lectures/03_maximum_likelihood_estimation.pdf)<br>[Video Lecture](https://youtu.be/MBRfst8Ab6o) | UML Section 24.1 |
| 4          | 19/09/2024 | Non-Parametric Methods: KDE, k-NN, and K-Means | [Slides](lectures/04_nonparametric_methods.pdf)<br>[Video Lecture](https://youtu.be/dN8buKnltEc?si=jf1-fOsjJ_gy12wQ) | UML Section 19, 22.2<br>ESL Section 2.3.2, 6.6.1, 13.3, 14.3<br>ISL 2.2, 12.4.1 |
| 5          | 24/09/2024 | Logistic Regression and Numerical Optimization | [Slides](lectures/05_logistic_regression.pdf)<br>[Video Lecture](https://youtu.be/LJBRT0c2I58?si=AAm7on8mOawXo_rI) | UML Section 9.3<br>ESL Section 4.4<br>ISL 4.3<br> PML 10-10.2.3<br>PRML 4.3.2 |
| 6          | 26/09/2024 | Maximum Margin Classifier and Constrained Optimization | [Slides](lectures/06_svm1_max_margin_classifier.pdf)<br>[Video Lecture](https://youtu.be/gcd939yYlUE?si=j06RHOsSXDGGNsME) | UML Section 15.1<br>ESL Section 4.5.2<br>ISL Section 9.1<br>PML Section 8.5, Section 17.3-17.3.2<br>PRML Section 7.1 (not including 7.1.1)|
| 7          | 01/10/2024 | Soft Margin Classifier | [Slides](lectures/07_svm2_soft_margin.pdf)<br>[Video Lecture](https://youtu.be/xVw-sHGxFKw?si=4a6NziwLMjmpJYD1) | UML Section 15.2,15.5<br>ESL Section 12.1-12.3.2<br>ISL Section 9.2-9.3<br>PML Section 17.3.3-17.3.4<br>PRML Section 7.1.1|
| 8          | 03/10/2024 | Kernel Methods | [Slides](lectures/08_kernel_methods.pdf)<br>[Video Lecture](https://youtu.be/AGG9KtbmS4Y?si=ysTwR4tclU7fbXg-) | PRML Section 6.1-6.3, 3-3.1.0<br>UML Section 16<br>ESL Section 5.8<br>PML Section 17.1<br>ISL Section 7-7.3  |
| 9a         | 08/10/2024 | Bayesian Inference | [Slides](lectures/09a_bayesian_inference)<br>[Video Lecture](https://youtu.be/TW1Qw1VIQWc) | PRML Section 3.1,3.3  |
| 9b         | 10/10/2024 | Gaussian Processes | [Slides](lectures/09b_gaussian_processes.pdf)<br>[Video Lecture](https://youtu.be/NwuvpJkl83M)<br>[Sampling Animation](lectures/9b_sampling_animation.gif) | PRML Section 6.4<br>PML Section 17.2 |
| 10         | 10/10/2024 | Decision Trees | [Slides](lectures/10_decision_trees.pdf)<br>[Video Lecture](https://youtu.be/2B-o3uB4OwI) | ESL Section 9.2<br>ISL Section 8.1<br>UML Section 10 |
| 11         | 10/22/2024 | Ensemble Methods | [Slides](lectures/11_ensemble_methods.pdf)<br>[Video Lecture](https://youtu.be/ffmQSTBRqQw) | PRML Section 3.2, 14<br>PML Section 18<br> ESL Section 7.1-7.3, 8.2, 8.7, 10.2, 10.10<br>ISL Section 8.1-8.2 |
| 12         | 10/24/2024 | Expectation Maximization & Gaussian Mixture Models | [Slides](lectures/12_expectation_maximization.pdf)<br>[Video Lecture](https://youtu.be/kQoitS2JTYs) | PML Section 8.7<br>ESL Section 8.5<br>PRML Section 9.1-9.5<br>UML Section 24.4 |
| 13         | 10/31/2024 | Multi-Layer Perceptrons and Deep Learning | [Slides](lectures/13_mlp_deep_learning.pdf) | D2L Section 5<br>DL Section 6,7<br>ISL Section 10-10.2, 10.6  |
| 14         | 05/11/2024 | Convolutional Neural Networks | [Slides](lectures/14_convolutional_nets.pdf) | D2L Sections 7, 8, 12<br>DL Sections 8, 9<br>ISL Section 10.3|
| 15         | 07/11/2024 | Recurrent Neural Networks | Slides TBD |   |
| 16         | 12/11/2024 | Attention | Slides TBD |   |
| 17         | 14/11/2024 | Graph Neural Networks | Slides TBD |   |
| 18         | 19/11/2024 | Variational Auto-Encoders and Generative Adversarial Networks | Slides TBD |   |
| 19         | 21/11/2024 | Flows | Slides TBD |   |
| 20         | 26/11/2024 | Robustness<br> (Guest Lecture from [Dr. P Michael Furlong](https://furlong.gitlab.io/))  | Slides TBD |   |
| 21         | 28/11/2024 | Privacy<br> (Guest Lecture from Saber Malekmohammadi) | Slides TBD |   |
| 22         | 03/12/2024 | Fairness<br> (Guest Lecture from [Dr. Terrence C. Stewart](https://compneuro.uwaterloo.ca/people/terrence-c-stewart.html)) | Slides TBD |   |

### :mag: Assignments
The four assignments will be posted here.

| ASSIGNMENT    | MATERIALS           | Posted   | Due Date |
| ------------- | ------------------- | -------- | -------- |
| 1             | [Assignment 1](assignments/a1) | 11 September 2024 | 27 September 2024 |
| 2             | [Assignment 2](assignments/a2) | 30 September 2024 | ~~18 October 2024~~<br>21 October 2024 |
| 3             | [Assignment 3](assignments/a3) | 23 October 2024 | 8 November 2024 |
| 4             | TBD | 12 November 2024 (tentative) | 22 November 2024 (tentative) |