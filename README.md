# Machine learning/Data science

## Description

This is a bundle compiling information (and snapshots of external repositories) related to Machine learning and Data science workshops and tutorials (if they don't have weight enough to deserve their one repository).

In particular, most content comes from the ODSC Masterclass Summit 2017 (held March 1-2 in San Francisco).

## Papers

`Deploying and Scaling Spark ML and Tensorflow AI Models.pdf` (from [https://github.com/fluxcapacitor/pipeline/wiki/ODSC-Masterclass-Workshop-Mar-01-2017](https://github.com/fluxcapacitor/pipeline/wiki/ODSC-Masterclass-Workshop-Mar-01-2017)) details the requirements for one of the masterclasses I didn't attend, about deploying and scaling.

## Masterclass repos

### Introduction to Deep Learning

First masterclass of the summit, during March 1.

* Remote:
* Repository: [https://github.com/dansbecker/ODSC-Intro-to-DL-Workshop.git](https://github.com/dansbecker/ODSC-Intro-to-DL-Workshop.git)

```
git remote add -f h2o_ml https://github.com/woobe/odsc_h2o_machine_learning.git
git subtree add --prefix python/odsc_h2o_machine_learning h2o_m
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

### Introduction to Machine Learning

I got this repository as a reference but didn't use it during the summit.

* Remote: `intro_ml_py`
* Repository: [https://github.com/amueller/introduction_to_ml_with_python.git](https://github.com/amueller/introduction_to_ml_with_python.git)

```
git remote add -f intro_ml_py https://github.com/amueller/introduction_to_ml_with_python.git
git subtree add --prefix python/introduction_to_ml_with_python intro_ml_py master --squash
```


### Introduction to scikit-learn

Repository: [https://github.com/amueller/odsc-masterclass-2017-morning](https://github.com/amueller/odsc-masterclass-2017-morning)

Morning masterclass about scikit-learn, during March 2.

### Advanced scikit-learn

Repository: [https://github.com/amueller/odsc-masterclass-2017-afternoon](https://github.com/amueller/odsc-masterclass-2017-afternoon)

Afternoon masterclass about scikit-learn, during March 2.

## External downloads

During the masterclass, the following products were used:

1. Data Science Studio from [Dataiku](https://www.dataiku.com/): The 4.0.1 version was [available as a free install](https://www.dataiku.com/dss/trynow/mac/). It is still avaible there as of 2017-04-11.

   That class was mainly a presentation of the product, so I didn't get to install it and play around with it.
