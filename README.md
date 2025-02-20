<!-- font: frutiger -->

> [!NOTE]  
> I no longer teach this course, so this material may not reflect the current curriculum.

# Machine Learning, 7.5 credits

<img src="Misc/linocut_water.png">


## Introduction and Aims

In this course you will learn how to formulate and organize practical machine learning problems, identify and estimate appropriate machine learning models for prediction and clustering, evaluate and select among different machine learning models and algorithms and implement machine learning models and algorithms in a programming language.

The course gives you knowledge about machine learning that is used within marketing, finance, economics, textual analysis, digital humanities and social sciences. You will encounter many different forms of data, including images and text.

The course covers a number of machine learning methods with a focus on prediction. The course deals with supervised and unsupervised machine learning as well as semi-supervised and active learning. The course includes flexible regression and classification, regularization, methods for predictive model performance evaluation, Gaussian processes, clustering algorithms and mixture models.

---

## Lecturers

<img src="Misc/villanipic.jpg" width="100">\
[Mattias Villani](https://mattiasvillani.com) \
Professor of Statistics, Stockholm and Linköping University\
Probabilistic machine learning and Bayesian methods

<img src="Misc/FrankOct2010.jpg" width="100">\
[Frank Miller](http://www.adoptdesign.de/frankmillereu/) \
Professor of Statistics, Stockholm University \
Experimental design, active learning and optimization methods

## Computer lab assistant

<img src="Misc/karl.jpeg" width="100">\
[Karl Sigfrid](https://www.su.se/english/profiles/kasi3175-1.513541) \
PhD student in Statistics, Stockholm University 


---
## Course description

The formal course description document with all the details about grading etc is [here](Misc/CourseDescriptionML.pdf).

## Course literature

The course will use the following book as the main course literature:

* **Machine Learning - a first course for engineers and scientists** (MLES) by Lindholm et al. (2021). Forthcoming at Cambridge University Press. A free PDF version is available [here](http://smlbook.org/book/sml-book-draft-latest.pdf). The previous title of the book was 'Supervised Machine Learning'.
* Additional course material linked from this page, such as articles and tutorials.
--- 

## Schedule

The course schedule on TimeEdit is here: [Schedule](https://cloud.timeedit.net/su/web/stud1/s.html?i=x7QeQ39x4nnyknbcQanQ6clvl1Z2ZZ0c02ndhcn_seXlYy603w575wgZuQnY).

---
## Lectures


Material under **Extra** are extra material that will help you understand the course content. \
Material under **Bonus** are not required course material, but may be of interest to the curious student.

**Lecture 1 - Introduction, k-NN and decision trees**\
Reading: MLES 1-2 |  [Slides](/Slides/ML_L1.pdf) \
Bonus: [Python Jupyter notebook for linear regression](/Code/LinReg.ipynb) | [Python code for nonlinear regression](/Code/RegData.py)

**Lecture 2 - Regularized non-linear regression and classification**\
Reading: MLES 3 |  [Slides](/Slides/ML_L2.pdf) \
Code: Spline regression: [Notebook](/Code/SplinesR.Rmd) [pdf](/Code/SplinesR.pdf) [html](/Code/SplinesR.html) | [Spline package demo](/Code/LidarSplines.R) \

**Lecture 3 - Evaluating predictive performance and hyperparameter learning**\
Reading: MLES 4 |  [Slides](/Slides/ML_L3.pdf) \
Bonus: [Some slides about entropy](/Slides/Entropy.pdf)

**Lecture 4 - Ensemble methods**\
Reading: MLES 7 |  [Slides](/Slides/ML_L4.pdf) \
Extra: [Gradient boosting visualized](http://arogozhnikov.github.io/2016/06/24/gradient_boosting_explained.html) | [Gradient boosting playground](http://arogozhnikov.github.io/2016/07/05/gradient_boosting_playground.html) 

**Lecture 5 - Learning from large-scale data**\
Reading: MLES 5 |  [Slides](/Slides/ML_L5.pdf) 

**Lecture 6 - Neural networks and Deep learning**\
Reading: MLES 6.1-6.2 |  [Slides](/Slides/ML_L6.pdf) \
Code: [Neural net MNIST in keras](/Code/kerasMNIST.R) \
Extras: [Video on Neural networks](https://youtu.be/aircAruvnKk) | [Video on learning a neural network](https://youtu.be/IHZwWFHWa-w) | [keras cheat sheet](/Misc/kerasCheatSheet.pdf)

**Lecture 7 - Image data and convolutional neural networks**\
Reading: MLES 6.3-6.4 |  [Slides](/Slides/ML_L7.pdf) \
Code: [ConvNet MNIST in keras](/Code/kerasMNISTConvNet.R) \
Extras: [Filter spreadsheet](/Code/Filters.xlsx) 

**Lecture 8 - Gaussian process regression and classification**\
Reading: MLES 9 |  [Slides](/Slides/ML_L8.pdf) \
Extras: [GP visualization](http://smlbook.org/GP/index.html) 

**Lecture 9 - Unsupervised learning - mixture models and clustering**\
Reading: MLES 10.1-10.3 |  [Slides](/Slides/ML_L9.pdf) \
Code: [EM for univariate Gaussian mixtures](/Code/GMM_EM.R) | [EM for multivariate Gaussian mixtures](/Code/GMM_EM_Multi.R)

**Lecture 10 - Textual data and topic models**\
Reading: [Multinomial-Dirichlet analysis](Literature/MultinomialDirichlet.pdf) | [Topic models intro](http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf) | [Slides](/Slides/ML_L10.pdf)

**Lecture 11 - Semi-supervised learning**\
Reading: MLES 10.1 |  [Slides](/Slides/MachineLearning11.pdf) 

**Lecture 12 - Active learning**\
Reading: [Settles (2010)](http://burrsettles.com/pub/settles.activelearning.pdf), especially Sections 1, 2, 3.1, 3.5, 3.6, 7.1 |  [Slides](/Slides/MachineLearning12.pdf) \
Code: [Active learning - illustrating example](/Code/active_learning_UD.r)

---
## Computer labs

* The three computer labs are central to the course. Expect to allocate substantial time for each lab. Many of the exam questions will be computer based, so working on the labs will also help you with the exam.

* R will be used as the course's programming language, see below for more info.

* The labs should be done in pairs of students.

* Each lab report should be submitted as a PDF along with the .R file with code. Submission is done through Athena.

* There are four hours of computer time allocated to each lab. The idea is that you: 
  * should start working on the lab before the computer session
  * so that you are in a position to ask questions at the session
  * and then finish up the report after the lab session.


**Computer Lab 1** - Regularized nonlinear regression and classification.\
Lab 1a: Regularized regression: [R notebook](/Labs/Lab1a.Rmd) | [pdf version](/Labs/Lab1a.pdf) | [html version](/Labs/Lab1a.html) \
Lab 1b: Regularized classification: [R notebook](/Labs/Lab1b.Rmd) | [pdf version](/Labs/Lab1b.pdf) | [html version](/Labs/Lab1b.html) \
Submission: Athena.

**Computer Lab 2** - Neural Networks and Gaussian Processes.\
Lab 2: [R notebook](/Labs/Lab2.Rmd) | [pdf version](/Labs/Lab2.pdf) | [html version](/Labs/Lab2.html) \
Submission: Athena.

**Computer Lab 3** - Unsupervised, semisupervised and active learning.\
Lab 3: [R notebook](/Labs/Lab3.Rmd) | [pdf version](/Labs/Lab3.pdf) | [html version](/Labs/Lab3.html) \
Submission: Athena.

### Lab assistant: [Karl Sigfrid](https://www.su.se/english/profiles/kasi3175-1.513541)

---

## Examination

The course examination consists of:

* Written lab reports (deadlines given in Athena)
* Computer exam


---

## R

* Analyzing data in R will be big part of the course, so you need to know a little R programming. The course [R programming 7.5 credits](https://www.su.se/english/search-courses-and-programmes/st4101-1.483412) or equivalent course is a prerequisite for this course. If you feel a little rusty on R, you can find a lot of material for studying it online, including tutorials, videos and free books. Here are some material:
  * [Download R](https://www.r-project.org/)
  * [RStudio](https://www.rstudio.com/products/rstudio/) - probably the best software/editor for R.
  * [Official introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)
  * [R Cheat sheets](https://www.rstudio.com/resources/cheatsheets/)
  * The labs and exam will be done using [R notebooks](https://blog.rstudio.com/2016/10/05/r-notebooks/) in RStudio. 
 
* Here are some machine learning packages in R: 
  * [Machine learning R packages](https://cran.r-project.org/web/views/MachineLearning.html) on CRAN.
  * **caret** - a meta package for predictive ML models in R. See the [Caret package vignette](https://cran.r-project.org/web/packages/caret/vignettes/caret.html)
 and a list of [available models](https://topepo.github.io/caret/available-models.html) in Caret.
   * **keras** - a package that brings Tensorflow for deep learning to R. Here is the [quick start to keras](https://tensorflow.rstudio.com/tutorials/beginners/).

---
