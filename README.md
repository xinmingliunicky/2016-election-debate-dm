# Decide people’s political leanings based on their tweet posts (2020 Fall DM)

* Team members: Xinming Liu, Jingyang Li, Xuezhi Xu



## Description
This data mining project aims to predict political leanings, typically the Democratic Party or the Republican Party, based on tweets during the 2016 US Presidential Debates. However, our methods also include text mining and data clustering besides classification.  

As is well-known, polls did not show significant predictive power back in 2016. Our purpose is to show that social media like Twitter did have certain predictive power that polls did not cover, yet should not be ignored.  

In text mining, TF-IDF, LSA, NMF and wordcloud projections are included.  

In clustering, we only used K-Means due to limited computation power.  

In classification, the models built include GLM, Naive Bayes, SVM with three types of kernels, Decision Tree and AdaBoost. Evaluation is basically focused on AUC.  

Please note that the main branch of this repository only contains our paper, presentation slides, project pitch and this README file. All the other codes and related results were separated in different branches with their names indicating the contents.

## Prerequisites
The R packages we used are all listed in the Rmd files. If you run the code chunks, RStudio should ask you to install them.  
The main packages used were "tm" for text mining, "caret" for supervised learning. Model-specific packages include "e1071" for Naive Bayes and SVM, "rpart" for classification trees, "ada" for AdaBoost, etc.

## Authors
Xinming Liu (xil231@pitt.edu)  
Jingyang Li 
Xuezhi Xu

## Acknowledgments
Thanks to our Prof. Lin for providing the [dataset](http://www.yurulin.com/class/spring2017_datamining/data/twitter_debate2016/).    

Thanks to StackOverflow users whose answers solved a lot of our problems:  
[Graeme Frost](https://stackoverflow.com/questions/51295402/r-on-macos-error-vector-memory-exhausted-limit-reached)  
[MrFlick](https://stackoverflow.com/questions/25171194/r-knn-categorization-with-documenttermmatrixes)  
[jlhoward](https://stackoverflow.com/questions/23580095/how-to-plot-clusters-with-a-matrix)  

Thanks to those who wrote great R tutorials:  
[suresh kumar Gorakala](https://www.r-bloggers.com/2013/07/document-classification-using-r/)
[Bryan Cole](https://rpubs.com/bmcole/reuters-text-categorization)  
[Ezgi](https://rpubs.com/ezgi/classification)  
[Jose James Campbell](https://rpubs.com/uky994/593668)  

### Inspiration
The pipline of our classification task (though not specific codes) is based on the wonderful example given by [Kory Becker](https://gist.github.com/primaryobjects/094d24084d1045c011b7).

## License
[MIT](https://choosealicense.com/licenses/mit/)
