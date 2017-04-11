# Machine learning/Data science

## Description

This is a bundle compiling information (and snapshots of external repositories) related to Machine learning and Data science workshops and tutorials (if they don't have weight enough to deserve their one repository).

In particular, most content comes from the ODSC Masterclass Summit 2017 (held March 1-2 in San Francisco).

## Papers

`Deploying and Scaling Spark ML and Tensorflow AI Models.pdf` (from [https://github.com/fluxcapacitor/pipeline/wiki/ODSC-Masterclass-Workshop-Mar-01-2017](https://github.com/fluxcapacitor/pipeline/wiki/ODSC-Masterclass-Workshop-Mar-01-2017)) details the requirements for one of the masterclasses I didn't attend, about deploying and scaling.

## Masterclass repos

### Introduction to Deep Learning

First masterclass of the summit, during March 1.

* Remote: `intro_dl`
* Repository: [https://github.com/dansbecker/ODSC-Intro-to-DL-Workshop.git](https://github.com/dansbecker/ODSC-Intro-to-DL-Workshop.git)

```
git remote add -f intro_dl https://github.com/dansbecker/ODSC-Intro-to-DL-Workshop.git
git subtree add --prefix python/intro_to_deep_learning intro_dl
```

### Machine Learning with H2O Open Platform

First afternoon masterclass about H2O, during March 1.

* Remote: `h2o_ml`
* Repository: [https://github.com/woobe/odsc_h2o_machine_learning.git](https://github.com/woobe/odsc_h2o_machine_learning.git)

```
git remote add -f h2o_ml https://github.com/woobe/odsc_h2o_machine_learning.git
git subtree add --prefix python/odsc_h2o_machine_learning h2o_ml master --squash
```


### Deep Learning with H2O Open Platform

Second afternoon masterclass about H2O, during March 1.

* Remote: `h2o_dl`
* Repository: [https://github.com/woobe/odsc_h2o_deep_learning.git](https://github.com/woobe/odsc_h2o_deep_learning.git)

```
git remote add -f h2o_dl https://github.com/woobe/odsc_h2o_deep_learning.git
git subtree add --prefix python/odsc_h2o_deep_learning h2o_dl master --squash
```

### Introduction to scikit-learn

Morning masterclass about scikit-learn, during March 2.

* Remote: `intro_skl`
* Repository: [https://github.com/amueller/odsc-masterclass-2017-morning.git](https://github.com/amueller/odsc-masterclass-2017-morning.git)

```
git remote add -f intro_skl https://github.com/amueller/odsc-masterclass-2017-morning.git
git subtree add --prefix python/odsc-masterclass-2017-morning intro_skl master --squash
```

### Advanced scikit-learn

Afternoon masterclass about scikit-learn, during March 2.

* Remote: `advanced_skl`
* Repository: [https://github.com/amueller/odsc-masterclass-2017-afternoon](https://github.com/amueller/odsc-masterclass-2017-afternoon.git)

```
git remote add -f advanced_skl https://github.com/amueller/odsc-masterclass-2017-afternoon
git subtree add --prefix python/odsc-masterclass-2017-afternoon advanced_skl master --squash
```

### Introduction to Machine Learning

This repository was used at the very end of the afternoon masterclass about scikit-learn, during March 2.

Notebook `07-working-with-text-data` is the last one we looked at and it is using the accompanying dataset extracted from [http://ai.stanford.edu/~amaas/data/sentiment/](http://ai.stanford.edu/~amaas/data/sentiment/), available here in `.tar.gz` format as `datasets/aclImdb_v1.tar.gz`.


* Remote: `intro_ml_py`
* Repository: [https://github.com/amueller/introduction_to_ml_with_python.git](https://github.com/amueller/introduction_to_ml_with_python.git)

```
git remote add -f intro_ml_py https://github.com/amueller/introduction_to_ml_with_python.git
git subtree add --prefix python/introduction_to_ml_with_python intro_ml_py master --squash
```


## Environment

During the masterclass, the following products were used:

1. Data Science Studio from [Dataiku](https://www.dataiku.com/): The 4.0.1 version was [available as a free install](https://www.dataiku.com/dss/trynow/mac/). It is still avaible there as of 2017-04-11.

   That class was mainly a presentation of the product, so I didn't get to install it and play around with it.
 
2. Everything else was Python based (I didn't attend any other course), and the environment is described (with minor updates) as `requirements.txt`.
