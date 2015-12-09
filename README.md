# cs109-project
cs 109 final project: Topic modeling with Supreme Court cases

Max Liebeskind, Madhu Vijay, Yunhan Xu

Github repo link: https://github.com/yunhanxu/cs109-project

This ReadMe has 4 sections: 
(I) GITHUB FILES, a list of all the files in our Github repo.
(II) Screencast link
(III) Website link
(IV) Libraries used: a list of all the non-ordinary libraries we used.

------------------------------------------------------------------------------------------------------

**I. GITHUB FILES**: below we have listed all of the files in our Github repo by file-type (iPython notebook, raw data files, other data files, miscellaneous). 

**iPython notebooks**

Our project is contained in multiple iPython notebooks, as permitted according to this Piazza post: https://piazza.com/class/icf0cypdc3243c?cid=1641. The notebooks (and links) are as listed below, *and should be read in the following order:*

1. intro_overview.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/intro_overview.ipynb
2. data_scraping.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/data_scraping.ipynb
3. data_merging.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/data_merging.ipynb
4. data_cleaning.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/data_cleaning.ipynb
5. naive_bayes_classification.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/naive_bayes_classification.ipynb
6. SVM.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/SVM.ipynb
7. NMF.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/NMF.ipynb
8. k-means.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/k-means.ipynb
9. lda.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/lda.ipynb) (note that lda.ipynb includes both the lda and the lsi models
10. mean-shift.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/mean_shift.ipynb
11. comparisons_and_conclusion.ipynb: https://github.com/yunhanxu/cs109-project/blob/project_data_collection/comparisons_and_conclusion.ipynb

**Raw data files**: this is where we got our raw data from.
- SCDB_2015_01_caseCentered_Citation.csv: this file is downloaded from http://scdb.wustl.edu/data.php (the Supreme Court Database). It contains information about every Supreme Court case since 1946.
- all_cases.csv: this file includes the scraped syllabi of all Supreme Court cases from 1946. Scraping has been done from https://supreme.justia.com/. The scraping process is explained in data_scraping.ipynb.

**Other data files**: these are data files that we have created for exporting data between notebooks.
- naive_bayes_full_model_results.csv: has various results and optimal parameters of naive bayes run on the full set of cases.
- naive_bayes_sample_model_results.csv: equivalent for the sample of cases.
- sample_cases.csv: this is the subsample of all_cases.csv that we train our models on.
- traintestarray.csv: a list of 0s and 1s to keep track of the training/test split in sample_cases.csv

**Miscellaneous** 
- SVM_image_1.png, SVM_image_2.png, kernelized_SVM_output.png: photos that we use in the notebooks.

------------------------------------------------------------------------------------------------------

**II. Screencast link**: 

------------------------------------------------------------------------------------------------------

**III. Website link**: http://cs109-project.squarespace.com/

------------------------------------------------------------------------------------------------------

**IV: Libraries**: we used the following non-ordinary libraries in our project. (These are libraries we used that were not frequently used in the course.)

- BeautifulSoup: http://www.crummy.com/software/BeautifulSoup/. Used for web scraping.
- Pattern: http://www.clips.ua.ac.be/pattern. Used for natural language processing; we use it to tokenize documents.
- Gensim: https://radimrehurek.com/gensim/. Used for LDA.
- Bottleneck: https://pypi.python.org/pypi/Bottleneck. Used for getting min/max values in arrays.
- Regex: https://docs.python.org/2/library/re.html. Used for text parsing. 
- Collections: https://docs.python.org/2/library/collections.html. Used for ordering dictionaries. 
