---
title: Class Notes
output:
  html_document:
    toc: yes
    toc_depth: 3
---

### Class notes for each topic will be posted here on a weekly basis.

### For lab exercises, links to downloadable .Rmd files will be included here.

[comment]: # (Uncomment hidden headers below as the semester progresses and add links to content)


### Week 1 - Intro
   + _**Background**_
      + [How to make a sex chromosome](https://raw.githubusercontent.com/cwheatlab/test_repo/pdf/How to make a sex chromosome.pdf)
      + R Markdown Intro - [HTML](week_01/R_Markdown_Intro.html) - [PDF](week_01/R_Markdown_Intro.pdf)
   + _**Homework Demo**_ - [HTML](week_01/HW_demo.html) - [PDF](week_01/HW_demo.pdf)
   + _**Exercise**_

### Week 2 - Working with Data: Data Frames, dplyr, ggplot
   + _**Background**_
      + [R Data Structures](https://kriscgun.github.io/xdas-bio-2018/r_resources/RDataStructures.html)
      + [_R for Data Science_, Irizarry and Love](http://r4ds.had.co.nz/)
      + [ggplot tutorial](week_02/ggplot_tutorial_week2.html)
      + Intro to ggplot2 - [HTML](week_02/dplyr-ggplots.md) - [RMD](week_02/dplyr-ggplots.Rmd)
   + _**Exercises**_
      + In-class exercise - [RMD](week_02/Week02_ex.Rmd)
      + [Review: HW and subsetting](week_02/Week_2_lab_reviewHW_and_datasubsetting.html)

### Week 3 - Summary Statistics, Distance measures; RNA-seq, Normalization
   + _**Background**_
      + Aho, Chapter 4.3: Summary statistics and distance measures - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Aho_Ch_4.3.pdf)
      + RPKM, FPKM, TPM (StatQuest, UNC Chapel Hill) - [VIDEO (10 mins)](https://www.youtube.com/watch?v=TTUrtCY2k-w)
   + _**Lecture notes**_
      + Summary statistics - [HTML](week_03/XDAS_SummaryStats.html) - [PDF](week_03/XDAS_SummaryStats.pdf)
      + Distance measures - [HTML](week_03/XDAS_Distance.html) - [PDF](week_03/XDAS_Distance.pdf)
      + RNA-seq and normalization - [HTML](week_03/XDAS_RNA-seq_Normalization.html) - [PDF](week_03/XDAS_RNA-seq_Normalization.pdf)    
   + _**Exercises**_
      + Distance calculations - [HTML](week_03/CalculatingDistanceByHand.html)
      + RNA-seq normalization lab - [HTML](week_03/RNA-seq-fpkm-tpm.md) - [RMD](week_03/RNA-seq-fpkm-tpm.Rmd)

### Week 4 - Clustering and Dimensional Reduction

#### Clustering
   + _**Background**_
      + Draghici, Chapter 11 - [PDF](week_04/Clustering_Draghici.pdf)
      + [Silhouette plot examples (scikit-learn)](http://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)
   + _**Lecture notes**_ Clustering - [HTML](week_04/Clustering.html) - [PDF](week_04/Clustering.pdf)
   + _**Exercise**_
      + Clustering By Hand [HTML](week_04/ClusteringByHand.html) - [RMD](week_04/ClusteringByHand.Rmd)

#### Dimensional Reduction: PCA and t-SNE
   + _**Background**_
      + Overview of PCA from ISLR (Introduction to Statistical Learning with R) - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/ISLR_PCA_overview.pdf)
      + [Introduction to dplyr (_R for Data Science_, Irizarry and Love)](http://r4ds.had.co.nz/transform.html#introduction-2)
      + Short videos from StatQuest (UNC Chapel Hill)
         + Overview of PCA with Singular Value Decomposition (SVD) - [VIDEO (22 mins)](https://www.youtube.com/watch?v=FgakZw6K1QQ)
         + PCA in R, step-by-step - [VIDEO (9 mins)](https://statquest.org/2017/11/27/statquest-pca-in-r-clearly-explained/)
   + _**Lecture notes**_
      + Dimensional Reduction with PCA - [HTML](week_04/Dimensional_Reduction_PCA.html) - [PDF](week_04/Dimensional_Reduction_PCA.pdf)
      + t-SNE - [HTML](week_04/Visualization_tSNE.html) - [PDF](week_04/Visualization_tSNE.pdf)
   + _**Exercises**_
      + PCA in R - [HTML](week_04/PCAbyHand.html) - [RMD](week_04/PCAbyHand.Rmd)
      + dplyr and PCA (Iris dataset) - [RMD](week_04/DplyrWithIris_Questions.Rmd)

### Week 5 - Introduction to Probability and Probability Density Functions

#### Introduction to Probability
   + _**Background**_ - Aho, Chapter 2: Introduction to Probability - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Aho_Ch2_Intro_Probability.pdf)
   + _**Lecture notes**_ - No lecture notes today (refer to assigned reading)

#### Probability Distributions, Part 1
   + _**Background**_
      + _**Review**_ - Tranchina, Elements of Calculus - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/CalculusReview_2.0.pdf)
      + _**Reading assignment**_ - Aho, Chapter 3.1-3.2: Probability Density Functions, Part 1 - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Aho_Ch3.1-3.2_Part1.pdf)
      + _**R functions for distributions: r, d, p, q**_ - Dalgaard, Chapter 3: R functions for sampling and probability distributions - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Dalgaard_ISR_Ch3.pdf)

   + _**Lecture notes**_ - Probability Distributions, Part 1 - [PDF](week_05/Discrete_and_Continuous_Distributions_I.pdf)
   + _**Exercise**_ - Coin Toss example - [HTML](week_05/CoinToss.html) - [RMD](week_05/CoinToss.Rmd)
   + _**Recitation**_ - Another PCA example - [HTML](week_05/recitation_pca.html) - [RMD](week_05/recitation_pca.Rmd)

### Week 6 - Probability Distributions, continued

#### Probability Distributions, Part 2
   + _**Background**_
      + Aho, Chapter 3.3-3.6: Probability Density Functions, Part 2 - [PDF](week_06/Aho_Ch3.3-3.6_PDFs_Part2.pdf)
   + _**Lecture notes**_ - [HTML](week_06/Discrete_and_Continuous_Distributions_II.html) - [PDF](week_06/Discrete_and_Continuous_Distributions_II.pdf)
   + _**Exercise**_ - What's my question?

### Week 7 - Simulations
  + In addition to the Coin Toss Simulation in Week 5, we also did the following:
  + _**Exercise**_
      + Ace Selection - [HTML](week_07/AceSelected.html) - [RMD](week_07/AceSelected.Rmd)
      + Marbles Selection - [HTML](week_07/MarbleSelection.html) - [RMD](week_07/MarbleSelection.Rmd)

### Week 8

#### Bootstrapping, p-values, and confidence intervals
   + _**Background**_
      + Statistics is Easy, Chapters 1 and 2 - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Statistics_is_Easy_Shasha.pdf)
   + _**Exercise**_ - Sampling from two groups - [HTML](week_08/StatsEasyTwoSample.md) - [RMD](week_08/StatsEasyTwoSample.Rmd)

#### Central Limit Theorem and the t-distribution
   + _**Background**_
      + **The Fickle P value** - Halsey et al., Nat Meth 2015 - [PDF](week_08/Halsey_P_value_NatMeth_2015.pdf)
      + Data Analysis for the Life Sciences, Irizarry and Love - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/dataanalysisforthelifesciences.pdf)
         + _**Central Limit Theorem and t-distribution**_ (pp. 34-62)
         + _Review (optional, read if you find helpful):_
            + Getting Started, pp. 4-13 (R basics)
            + Inference, pp. 18-34 (Random variables, null hypothesis, distributions; populations, samples and estimates)
      + Introductory Statistis with R, Dalgaard - Chapter 5: One- and two-sample tests - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Introductory_Statistics_with_R_Dalgaard.pdf)
   + _**Exercise and Class Notes**_
      + DQPR - [HTML](week_08/Intro_to_dqpr_functions_in_R_v2.html) - [RMD](week_08/Intro_to_dqpr_functions_in_R_v2.Rmd)
      + CLT and sample estimates - [HTML](week_08/XDAS_CLT_KEY_v2.html) - [RMD](week_08/XDAS_CLT_KEY_v2.Rmd)
   + _**Lab**_    
      + t-distribution, t-test, & p-values- [RMD](week_08/Pvalue_lab_Stats.Rmd)   		


### Week 9 - ANOVA
+ _**Background**_
    + Modern Statistics for the Life Sciences, Grafen and Hails - Chapter 1: An introduction to analysis of variance - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Grafen_Hails_Ch1_ANOVA.pdf)
    +  Introductory Statistis with R, Dalgaard - Chapter 7: Analysis of variance and the Kruskal-Wallis test - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Introductory_Statistics_with_R_Dalgaard.pdf)
+ _**Exercise**_
    + Chi-Square and ANOVA [HTML](week_09/ANOVA2_kcg.html) - [RMD](week_09/ANOVA2_kcg.Rmd)
    + Linear Models [HTML](week_09/LinearModels.html) - [RMD](week_09/LinearModels.Rmd)
    + Multiple Factorial ANOVA [HTML](week_09/MultAnova.html) - [RMD](week_09/MultAnova.Rmd)


### Week 10 - ANOVA, Type I and II Error, Power, Multiple Hypothesis Testing

+ _**Background: ANOVA**_
    + Modern Statistics for the Life Sciences, Grafen and Hails
        - Chapter 1: An introduction to analysis of variance - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Grafen_Hails_Ch1_ANOVA.pdf)
        - Chapter 4: Using more than one explanatory variable - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Grafen_Hails_Ch4_Multiple_Explanatory_Variables.pdf)
        - Chapter 7: Interactions - getting more complex - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Grafen_Hails_Ch7_Interactions.pdf)
+ _**Exercise**_
    + CO2 and ANOVA [HTML](week_10/CO2_anova_question.html) - [RMD](week_10/CO2_anova_question.Rmd)
    + Multiple Factorial ANOVA [HTML](week_09/MultAnova.html) - [RMD](week_09/MultAnova.Rmd)

+ _**Background: Type I and II Error, Power, Multiple Hypothesis Testing**_
    +  Aho, Chapter 6.3-6.5 - [PDF](week_10/Aho_Hypothesis_Error_Power.pdf)
    + McDonald, Handbook of Biological Statistics: [Multiple Comparisons](http://www.biostathandbook.com/multiplecomparisons.html)
+ _**Class Notes**_
    + Type I and II Error, Power, Multiple Testing - [PDF](week_10/Error_Power_MultCorrection.pdf) - [HTML](week_10/Error_Power_MultCorrection.html)
+ _**Exercise**_
    + FDR Exercise - [RMD](week_10/FDR_exercise.Rmd)

### Week 11 - Regression and Correlation
+ _**Background: Regression**_
    + Modern Statistics for the Life Sciences, Grafen and Hails
        - Chapter 2: Regression - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Grafen_Hails_Ch2_Regression.pdf)
    + Introductory Statistis with R, Dalgaard -
        - Chapter 6: Regression and Correlation - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/Introductory_Statistics_with_R_Dalgaard.pdf)
+ _**Exercise**_
	+ Regression vs. Correlation [HTML](week_11/XDAS_Regression.html) - [RMD](week_11/XDAS_Regression.Rmd)
	+ LM and Regression Worksheet [RMD](week_11/LM_exercise2018ques.Rmd)
	    - Answers [HTML](week_11/LM_exercise2018.html) - [RMD](week_11/LM_exercise2018.Rmd) - [RMD](week_11/XDAS_Regression.Rmd)

+ _**Videos: Regression**_
	+ Khan Academy [LINK](https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/regression-library/v/introduction-to-residuals-and-least-squares-regression)

+ _**Background: Logistic Regression**_
     + Introduction to Statistical Learning, Chapter 4: Classification - [PDF](https://kriscgun.github.io/xdas-bio-2018/references//ISL_Ch4_LogisticRegression.pdf)
+ _**Lecture notes: Logistic Regression**_
     + Logistic Regression - [PDF](week_11/Logistic_Regression.pdf)

+ _**Wisconsin Breast Cancer**_
     + Question and Answer [HTML](week_11/WisconsinCancerLR.html) - [RMD](week_11/WisconsinCancerLR.Rmd)

### Week 12 - Cross Validation and ROC curves

+ _**Background: Cross Validation**_
     + Introduction to Statistical Learning, Chapter 5: Resampling and Cross Validation - [PDF](https://kriscgun.github.io/xdas-bio-2018/references/ISL_Ch5_CV.pdf)
+ _**Lecture notes: Logistic Regression**_
     + Cross Validation - [PDF](week_12/CrossValidation.pdf)


### Week 13 - Nonparametric Methods and Tabular Statistics
+ _**Background: Nonparametric Methods**_
	+ Wilcoxon Signed Rank Test - Dalgaard (sections 5.2 and 5.5)
	+ Kruskal-Wallis and Friedman Test - Dalgaard (sections 7.2 and 7.4)
	+ Nonparametric methods - Rosner (Ch. 9 , 12.7) - [PDF](week_13/Rosner_Chapter9_NonparametricMethods.pdf)
	+ Rank Correlation - Rosner (Ch. 11.12- 11.13)
+ _**Lecture notes: Nonparametric Methods**_
	+ Wilcox Signed-Rank, Wilcox Rank Sum, Spearman - [HTML](week_13/NonParametric_2018.html) - [RMD](week_13/NonParametric_2018.Rmd)
	+ Wilcox Rank Sum Exercise - [RMD](week_13/WilcoxRankSumEx.Rmd)
	+ Wilcox Rank Sum Exercise Answer - [HTML](week_13/WilcoxRankSumExAns.html)  - [RMD](week_13/WilcoxRankSumExAns.Rmd)

+ _**Background: Tabular Statistics**_
	+ Hypothesis Testing: Categorical Data - Rosner (Ch. 10.1-10.3) - [PDF](week_13/Rosner_Chapter10_CategoricalData.pdf)
	+ Hypothesis Testing: Categorical Data - Aho (Ch. 11.1 - 11.6)

+ _**Lecture notes: Tabular Statistics (corrected)**_
        + Long version - [HTML](week_13/TabularStats_kcg2.html) - [RMD](week_13/TabularStats_kcg2.Rmd)
        + Short version - [HTML](week_13/TabularStats_kcg2_short.html) - [RMD](week_13/TabularStats_kcg2_short.Rmd)
        + Student version - [RMD](week_13/TabularStats_kcg2_student_version.Rmd)

### Week 14 - Gene expression exercise

+ Files:
  - Paper: [Hashimshony 2015 (PDF)](week_14/Hashimshony_Yanai_Nature2015.pdf)
  - Dataset: [CSV](week_14/C_elegans_whole_embryo.csv)
  - GeneIDs: [TXT](week_14/C_elegans.WS230.geneIDs.txt)

+ Exercise: [HTML](week_14/XDAS_2018_Timeseries_Exercise.html) - [RMD](week_14/XDAS_2018_Timeseries_Exercise.Rmd)
  - KEY for Part 1: [HTML](week_14/XDAS_2018_Timeseries_Part1_KEY.html) - [RMD](week_14/XDAS_2018_Timeseries_Part1_KEY.Rmd)


[comment]: # (* **Week 14 - Title**)
