# Applied Statistics
## About This Project
This project explores statistical concepts and hypothesis testing through Python programming. Key tasks include:
* Calculating probabilities using permutations and combinations.
* Analyzing a normal distribution with synthetic data.
* Performing a paired t-test on a real-world dataset of heart rates.
The project demonstrates practical applications of libraries such as **numpy**, **scipy**, **pandas**, **matplotlib**, and **seaborn** for statistical analysis and data visualization.
## Use of This Project
This project is designed for anyone interested in learning statistical methods and Python programming. 
## Getting Started
### Prerequisites
* Python 3.9+
* Jupyter Notebook
* Required libraries:
    * numpy
    * scipy
    * pandas
    * matplotlib
    * seaborn
Install the libraries using:

```bash
pip install numpy scipy pandas matplotlib seaborn
```
* Running the Code:

Clone the repository:
```bash
git clone <repository-url>
cd <repository-directory>
```
Run the Python scripts in your preferred IDE or terminal.
To work with the PlantGrowth R dataset download it using this [link](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv)<br>
## Getting Help
Refer to the documentation of the libraries used:

[Numpy Documentation](https://numpy.org/doc/)<br>
[Scipy Documentation](https://docs.scipy.org/doc/scipy/)<br>
[Pandas Documentation](https://pandas.pydata.org/docs/)<br>
[Matplotlib Documentation](https://matplotlib.org/stable/index.html)<br>
[Seaborn Documentation](https://seaborn.pydata.org/)<br>
## Tasks Overview
### Task 1: Permutations and Combinations
This task explored the chances of guessing correctly in a modified [Lady Tasting Tea experiment](https://en.wikipedia.org/wiki/Lady_tasting_tea) using Python. It included:
* Calculating the probability of picking all six correct cups out of twelve by guessing.
* Finding the probability of making at most one mistake (getting at least five correct).
* Deciding if allowing two mistakes would still make the claim believable.
### Task 2: numpy's Normal Distribution
This task examined the accuracy of the numpy.random.normal() function in generating values from a normal distribution. The steps included:
* Generating a sample of 100,000 values with a mean of 10.0 and a standard deviation of 3.0.
* Using scipy.stats.shapiro() to test if the sample follows a normal distribution and interpreting the results.
* Creating a histogram of the sample and overlaying the corresponding normal distribution's probability density function to visualize the comparison.
### Task 3: t-Test Calculation
Analyzed heart rate data before and after a two-week exercise program by calculating the t-statistic manually and comparing it with scipy.stats.
### Task 4: ANOVA
In this task, the one-way ANOVA test was performed 10,000 times to assess the occurrence of Type II errors.
### Project
The aim of the project is to analyze [the PlantGrowth R dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv). A brief description of the dataset can be found on Vincent Arel-Bundock's Rdatasets [page](https://vincentarelbundock.github.io/Rdatasets/doc/datasets/PlantGrowth.html). The dataset contains results from an experiment designed to compare the yields (measured as the dried weight of plants) under three different conditions.
**Source af data:** Dobson, A. J. (1983) An Introduction to Statistical Modelling. London: Chapman and Hall.
##### Tasks:
* Dataset Preparation<br>
* Data Description<br>
* Explain Statistical Methods<br>
* $t$-test<br>
* ANOVA<br>
* Summary<br>
## Contribute
Contributions are welcome! Clone the repository, make your improvements or suggestions, and submit a pull request.
## References
[Lady Tasting Tea experiment](https://en.wikipedia.org/wiki/Lady_tasting_tea)<br>
[Python math.comb() Method](https://www.w3schools.com/python/ref_math_comb.asp)<br>
[Python – Itertools Combinations() function](https://www.geeksforgeeks.org/python-itertools-combinations-function/)<br>
[Python Set intersection() Method](https://www.w3schools.com/python/ref_set_intersection.asp)<br>
[numpy.unique](https://numpy.org/devdocs/reference/generated/numpy.unique.html)<br>
[numpy.random.normal](https://numpy.org/doc/2.0/reference/random/generated/numpy.random.normal.html#numpy-random-normal)<br>
[Shapiro-Wilk test](https://www.geeksforgeeks.org/how-to-perform-a-shapiro-wilk-test-in-python/)<br>
[Alpha level](https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/what-is-an-alpha-level/)<br>[How to Plot Normal Distribution over Histogram in Python](https://www.geeksforgeeks.org/how-to-plot-normal-distribution-over-histogram-in-python/)<br>
[Types of $t$-test](https://datatab.net/tutorial/t-test)<br>
[$t$-tests in Python](https://www.datacamp.com/tutorial/an-introduction-to-python-t-tests?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720824&utm_adgroupid=157156376311&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=720362650453&utm_targetid=dsa-2218886984100&utm_loc_interest_ms=&utm_loc_physical_ms=1007890&utm_content=&utm_campaign=230119_1-sea~dsa~tofu_2-b2c_3-row-p2_4-prc_5-na_6-na_7-le_8-pdsh-go_9-nb-e_10-na_11-na-bfcm24&gad_source=1&gclid=Cj0KCQiAi_G5BhDXARIsAN5SX7pQ0aY0QXyd2Ix2RLW2lQYol1FE9E3dYWeKhhA_uoVpgOi7zTYLsmYaAnkIEALw_wcB)<br>
[ttest_rel](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_rel.html)<br>
[Two Sample T-Test in Python](https://www.geeksforgeeks.org/how-to-conduct-a-two-sample-t-test-in-python/)<br>
[$t$-test assumptions](https://statistics.laerd.com/statistical-guides/independent-t-test-statistical-guide.php)<br>
[Significance level](https://statisticsbyjim.com/glossary/significance-level/)<br>
[Statistics (scipy.stats)](https://docs.scipy.org/doc/scipy/tutorial/stats.html)<br>
[Type I and Type II errors](https://en.wikipedia.org/wiki/Type_I_and_type_II_errors)<br>
[The one-way ANOVA](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html)<br>
[Levene’s test](https://www.geeksforgeeks.org/levenes-test/)<br>
[Itertools Combinations() function](https://www.geeksforgeeks.org/python-itertools-combinations-function/)<br>
## Author
Katerina Lisovenko
Atlantic Technological University Student (2024-2025)
### Disclaimer
AI tools, including GPT-3 (ChatGPT), were used to assist with style and grammar checks, as well as to research additional solutions, while ensuring the accuracy and quality of the work.