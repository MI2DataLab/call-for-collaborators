# Summer is Coming

MI2 Data Lab is looking for students for summer internships.
The internship takes 2 months. It can be either June-July or July-August or August-September 2019.
Projects for internships are related with [eXplainable Artificial Intelligence or AutoML/AutoEDA tools developed in the MI2DataLab](https://github.com/ModelOriented/DrWhy/blob/master/README.md).

For the two-months internship, you can expect 5000 net / 5500 gross paid as a contract to perform a specified task.

Developed packages and libraries will be released as open-source packages under GPL license. Best projects can be turned to research articles.

XAI and AutoML are the hottest trends in AI/ML. Join our team to work on them.

## How to apply

Please send an email to `przemyslaw.biecek` at `gmail.com` with

-    your resume, 
-    short (5 sentences max) description of the most interesting project that you have worked on,
-    selected projects that you would like to work on.


# Projects

These are short summaries. Please mail me if you want to learn more details.

We expect that you are familiar with `R`, you know good practices of code development and you can write technical documentation in English.

We DO NOT expect that you already know `DALEX`, `archivist` or `pkgdown` packages. You will learn them during the internship. 



## Archivist for pkgdown

Integration of `archivist` hooks in the `pkgdown` package. Enriched technical documentation with `archivist` links.

The `archivist` helps to store and manage artifacts created in R, while `pkgdown` converts documentation and vignettes into attractive and useful website. The combination of `archivist` and `pkgdown` would allow users to download R-objects from the generated page.

Learn more about `archivist` at https://github.com/pbiecek/archivist and https://www.jstatsoft.org/article/view/v082i11

## ML for cloud

Development of cloud-based model store. 

There are tools to manage storage and access of machine learning features, such as `feast`. Why not create something similar for the models?  Such a store would serve a number of applications in AutoML problems.

Learn more about feature store at https://github.com/gojek/feast

## Champion vs Challenger XAI explainers

Extension of the `modelDown` package (https://github.com/MI2DataLab/modelDown) to a tool for contrastive comparisons of two ML models. 

Now, the `modelDown` generates a comprehensive explanation of a single model, however, Data Scientists ofen face with the choice between several models. That's why we need tools which make it easier to compare models.

Learn more about `DALEX` at http://jmlr.org/papers/v19/18-416.html and `modelDown` at https://github.com/MI2DataLab/modelDown_example

## Unit Tests for Models

Extension of models' scores implemented in the `auditor` and implementation of automated unit tests for models (similar to tests in `testthat`).

The `auditor` provides an easy to use unified interface for creating validation plots for any model. This visualizations allow to asses and compare the goodness of fit, performance, and similarity of models. In addition to the visual evaluation of the model, numerical measurements are also important. Since software testing with unit tests is so common, why not do the same with models? Such tests would allow detecting problems (e.g. concept drift) with models which were already deployed into production.

Learn more about `auditor` at https://github.com/MI2DataLab/auditor and `testthat` at https://testthat.r-lib.org/ 
