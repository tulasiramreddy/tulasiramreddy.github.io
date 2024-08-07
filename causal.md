**Course**:  Causal Inference and Discovery (DS3223/DS6273/MT3273/MT6433)

**Lecture hall**: LHC 301 (NKN classroom);

**Virtual link**: [Google meet](https://meet.google.com/zcq-cdzj-qvs)

**Instructor**: Tulasi Ram Reddy (tulasimath 'at' gmail 'dot' com; Room No: 406)

**TA**: Mihir Hasabnis (mihirhasabanis 'at' gmail 'dot' com; Room No: )

**Office hours**: 

[![Correlation](https://raw.githubusercontent.com/tulasiramreddy/tulasiramreddy.github.io/master/correlation.png)](https://xkcd.com/552/ "Correlation doesn't imply causation, but it does waggle its eyebrows suggestively and gesture furtively while mouthing 'look over there'.")


**Topics to be covered:** Simpson's paradox, Structural Causal Model (SCM), Design of Experiments, Potential Outcomes Framework, Causal Graphical Model, d-separation, do-operator,  Rubin's G-formula, Causal Discovery, If time permits: Regression Discontinuity Designs, Difference in Differences, Instrumental Variables Estimation.

**Prerequisites**: Familiarity with basic statistical concepts such as estimation techniques, hypothesis testing, and probability distributions. Exposure to regression analysis, including simple linear regression and multiple regression, is essential. Understanding  of Linear algebra and  multivariate calculus (derivatives and integrals)  (derivatives and integrals) is necessary. Further knowledge of graphs and properties is useful.

| Lecture   | Date   | Contents     | Supplementary material |
| :------------- | :----------: | -----------: | -----------: |
| 1|   1-January  | Introduction  | [John Snow and 1854 Cholera outbreak](https://en.wikipedia.org/wiki/1854_Broad_Street_cholera_outbreak) |
| 2|  11-January  | Simpson's Paradox | See Chapter-1 from [ Peng Ding's lecture notes](https://arxiv.org/pdf/2305.18793.pdf)|
| 3|  13-January  | Review   | [Properties of Gaussian random variables](http://math.iisc.ac.in/~manju/GP/1-Gaussian%20random%20variables.pdf) (From a lecture notes by Manjunath Krishnapur )|
| 4|   13-January  | Partial regression  | *Class test-I on 16-January-2024* |
| 5|  15-January  | Treatments, effects and confounders | |
| 6|  18-January  | Potential outcomes framework (Neyman/Rubin's causal model) |  |
| 7|   20-January  |  Causal Graphical Model  |*Class test-II on 1-February-2024*  |
| 8|  25-January  | d-Separation | |
| 9|   29-January  |  Structural Causal Model | For SCM and related topics you may see Chapters-3 and 6 from the book [Elements of Causal Inference: Foundations and Learning Algorithms](https://mitpress.mit.edu/9780262037310/elements-of-causal-inference/) by J. Peters, D. Janzing and B. Schölkopf |
| 10|  30-January  | Robin's G-formula/Trucated Factorization |  Check [DAGitty](https://www.dagitty.net/)|
| 11|   6-February  |   Backdoor criteria| *Class test-III on 15-February-2024* |
| 12|  10-February  | Adjustment formula | For topics until Mid-Sem, you may refer Chapters 1, 2 and 3 from the book [Causal Inference in Statistics](http://bayes.cs.ucla.edu/PRIMER/) by J. Pearl, M. Glymour, N. P. Jewell |
| 13|   12-February  | Front door criteria |  |
| 14|  13-February  | Matching | |
|| 23-February| Mid-Semester Exam| |
| 15|  27-February  | Propensity score |Python packages: [DoWhy](https://www.pywhy.org/dowhy/v0.8/getting_started/intro.html), [EconML](https://econml.azurewebsites.net/index.html), [causal-learn](https://causal-learn.readthedocs.io/en/latest/index.html) |
| 16|   4-March  | IPW  |  |
| 17|   11-March  |  Makeup Lecture |  |
| 18|  18-March  | Instrumental Variables-1  |[Two-Stage Least Squares Estimation of Average Causal Effects in Models with Variable Treatment Intensity](https://www.tandfonline.com/doi/abs/10.1080/01621459.1995.10476535) by Guido W. Imbens and Joshua D. Angrist|
| 19|   19-March  |  Instrumental Variables -2 | [Identification and Estimation of Local Average Treatment Effects](https://www.jstor.org/stable/2951620) by Guido W. Imbens and Joshua D. Angrist|
| 20|  26-March  | Instrumental Variables-3 |  |
| 21|  30-March  | Regression Discontinuity Designs - 1 | |
| 22|   30-March  | Regression Discontinuity Designs - 2 |    |
| 23|    1-April| Difference in Differences (DID) -1 |   [Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania](https://www.jstor.org/stable/2118030) by David Card and Alan B. Krueger|
| 24|   2-April  |Difference in Differences (DID) -2 | For topics after Mid-Sem, you may refer Chapters 5, 6, 7, 9  in [Causal Inference: The mixtape](https://mixtape.scunning.com/) by Scott Cunningham |
| 25| 8-April | Causal Discovery (PC Algorithm)| [Introduction to the foundations of causal discovery](https://link.springer.com/article/10.1007/s41060-016-0038-6) |
| 26| 13-April|Independence tests, Algorithms(FCI/GES/LiNGAM)| [Causal Discovery Methods Based on Graphical Models](https://www.frontiersin.org/articles/10.3389/fgene.2019.00524/full)|
||29-April| End-Semester Exam|Due date for class projects submission|


**Problem Sets:** | [Set-1](https://www.dropbox.com/scl/fi/8mqo8azk9x221rq9gflac/CI_set-1.pdf?rlkey=l5pal6pi4vov760ot9qy14irh&dl=0) | [Set-2](https://www.dropbox.com/scl/fi/ic317h0yqxcgl7lbh4rc4/CI_set-2.pdf?rlkey=siv5clxk5cdn3074zqv3bs6l2&dl=0) | [Set-3](https://www.dropbox.com/scl/fi/gjdz7cvszzvzi2vaqmcrb/CI_set-3.pdf?rlkey=wmouhmcqknj0vbr4kmvnfslad&dl=0)


<!--- **Class Projects**

| Title | Relevant material and links | Presenters |
|:----|:----:|:----:|
| Proof of equivalence of Bayesian Factorization and Markov Property and  an algorithm (with implementation) to verify d-separation| |Nikhil, Amruthamshu, Moksh, Sneha |
| Estimating Treatment Effects with Causal Forests: An Application |[ArXiv link](https://ar5iv.labs.arxiv.org/html/1902.07409) \ [Related paper](https://doi.org/10.1214/18-AOS1709)| Vihang, Vivek and Aastha, Paarth, Shinjini|
| Sensitivity analysis of linear Structural Causal Models| [JMLR link](http://proceedings.mlr.press/v97/cinelli19a.html) | |
|Introduction to Double Robust Methods for Incomplete Data| [Journal Paper link](https://projecteuclid.org/journals/statistical-science/volume-33/issue-2/Introduction-to-Double-Robust-Methods-for-Incomplete-Data/10.1214/18-STS647.full)||
|Permutation-based Causal Inference Algorithms with Interventions | [NIPS link](https://papers.nips.cc/paper/2017/hash/275d7fb2fd45098ad5c3ece2ed4a2824-Abstract.html) | |
| The Effect of Age at School Entry on Educational Attainment: An Application of Instrumental Variables with Moments from Two Samples| [JSTOR Link](https://www.jstor.org/stable/2290263) | |
|Kernel Instrumental Variable Regression|[NIPS Link](https://proceedings.neurips.cc/paper/2019/hash/17b3c7061788dbe82de5abe9f6fe22b3-Abstract.html)||
|Causal inference in economics and marketing|[PNAS Link](https://www.pnas.org/doi/full/10.1073/pnas.1510479113#bibliography)|Sushant, Vishnu |
|Mendelian randomization in health research: Using appropriate genetic variants and avoiding biased estimates|[Journal Paper Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3989031/)||
| RDD/DID | | |
| Causal Reasoning and Large Language Models: Opening a New Frontier for Causality | [ArXiv link](https://ar5iv.labs.arxiv.org/html/2305.00050) | | --->


**References:**
- [Elements of Causal Inference: Foundations and Learning Algorithms](https://mitpress.mit.edu/9780262037310/elements-of-causal-inference/) by J. Peters, D. Janzing and B. Schölkopf
- [Causal Inference in Statistics](http://bayes.cs.ucla.edu/PRIMER/) by J. Pearl, M. Glymour, N. P. Jewell
- [Causality: Models, Reasoning and Inference](http://bayes.cs.ucla.edu/BOOK-2K/) by Judea Pearl
- [Causal Inference for Statistics, Social, and Biomedical Sciences](https://www.cambridge.org/core/books/causal-inference-for-statistics-social-and-biomedical-sciences/71126BE90C58F1A431FE9B2DD07938AB) by G. W. Imbens and D. B. Rubin
- [Causal Inference: What if?](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) by M. A. Hernan and J. M. Robins
- [Causal Inference: The mixtape](https://mixtape.scunning.com/) by Scott Cunningham  
<!---  -[Experimental Design: Lecture Notes](https://artowen.su.domains/courses/363/doenotes.pdf) by [Art Owen](https://artowen.su.domains/)    ---> 
- [Causal Inference: Lecture Notes](https://web.stanford.edu/~swager/stats361.pdf) by [Stefan Wager](https://web.stanford.edu/~swager/)
- [A First Course in Causal Inference](https://arxiv.org/abs/2305.18793) lecture notes by [Peng Ding](https://sites.google.com/site/pengdingpku/)
- [Statistics and Causal Inference](https://www.jstor.org/stable/2289064) by Paul W. Holland (appeared in JASA 1986)
