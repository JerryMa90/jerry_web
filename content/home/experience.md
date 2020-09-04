+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Data Scientist Internship"
  company = "Microsoft"
  company_url = "https://www.microsoft.com/en-us/"
  location = "Redmond, Washington"
  date_start = "2020-06-08"
  date_end = "2020_08_21"
  description = """
  Projects:

    1. Benchmarking of differential privacy (DP) algorithms:
      - Created an interface-based DP benchmarking framework in collaboration with Harvard University to be ingested in OpenDP Core library.
      - Built a set of of DP visualization capabilities for the framework containing rich Python based graphs and animations to showcase and compare certain algorithms' performance.
      - Made a notebook of sample code that researchers can use as a template for their own DP algorithms.


    2. Hackathon Projects:
      - Python Programming Puzzles:
        Brainstormed more than 100 puzzles together with 35 'hackers' and tried to solve each other's.
        Followed up on a trained an Abstract Syntax Tree (AST) deep learning model to teach a PC to solve puzzles automatically.
      - Metabolomics AI driven Research Service (MARS):
        Collaborated with Microsoft Research experts and Professor Thomas O’Connell and tapped into four public data sources and built a brand new AI driven NLP system to dramatically improve the correlations of 30+ million research papers focusing on around 100K metabolites and their usefulness in treating both COVID-19 and different types of cancer.


  Paper accepted:

    Title: Distributed Differentially Private Mutual Information Ranking and Its Applications
    Coauthors: Ankit Srivastava, Samira Pouyanfar, Joshua Allen, Ken Johnston
  """

[[experience]]
  title = "Teaching Assistant"
  company = "Department of Statistical Science, Baylor University"
  company_url = "https://www.baylor.edu/statistics/"
  location = "Waco, Texas"
  date_start = "2017-06-01"
  date_end = ""
  description = """
  TA responsibilities:
  
  * Assist undergraduates in statistical tutoring labs.
  * Grade assignments and quizzes for computational statistics course.
  * Built solution menus for graduate mathematical statistics courses.
  
  Projects:
  * Developed a heteroskedastic linear dimension reduction (HLDR) method to better classify state financial success with R. Evaluated different classification methods including QDA, KNN and Random Forest.
  * Proposed a “Sampling + Autoencoder” algorithm to numerically parameterize real varieties with R. Implemented Hamiltonian Monte Carlo methods, Homotopy endgames, Autoencoder Neural Network and Natural Cubic Splines with R (Stan and Keras/Tensorflow).
  * Deduced theoretical derivations for different types of confidence intervals for a poisson rate parameter with a misclassification nuisance parameter including Wald, score and integrated-likelihood methods. Conducted Monte Carlo simulations and real data example study with R.
  
  Publications:
  * Q. Ma, J. Patrick, L. Njoh, and D. Young.“Integrated-Likelihood-Ratio Confidence Intervals for a Poisson Rate Parameter and Misclassification Parameter Using Double Sampling.” (Under peer review)
  * Q. Ma, J. Patrick, P. Young, D. Young, and L. Njoh. “A Double-Sampling Based Integrated-Likelihood-Ratio Confidence Interval for a Poisson Rate with Over- and Under-Counted Data.” (In preparation)
  * Q.Ma and D. Kahle. “Parameterizing Varieties with Deep Learning.” (In preparation)
  
  Talks:
  * Q. Ma and D. Kahle. “Parameterizing Varieties with Deep Learning.” The 2nd Annual Meeting of SIAM
Texas-Louisiana Section, Southern Methodist University, Dallas, Texas, USA, November 1–3, 2019.
  """

[[experience]]
  title = "Data Analyst"
  company = "CreditEase"
  company_url = ""
  location = "Beijing, China"
  date_start = "2014-11-01"
  date_end = "2017-01-01"
  description = """
  Responsibilities include:
  
  * Designed and developed the first Auto Loan Credit Scoring system for classifying new customers into different levels based on their credit information with R, which used to support auto loan marketing.
  * Conducted dimension reduction and variable selections with different techniques including stepwise variable selection, LASSO, Ridge regression, Elastic Net, PCA, etc.
  * Evaluated different classification methods for the Credit Scoring system, including multinomial logistic regression, random forest, gradient boosting, etc.
  * Cleaned and manipulated P2P loan service datasets with millions of observations and thousands of features with SQL.
  * Designed and maintained monthly and seasonal risk reports with R.
  * Automated the generation and notification of daily risk reports for leadership reviews.
  """
  

+++
