# tensorflow-intro

My Jupyter notebook from the Monash DataFluency **_Tensor Flow and Machine Learning_** workshop.

The notebook makes use of the DataFluency `TutorialSupport` package and sample data.

To get started, clone this repository:

```bash
$ $ git clone https://github.com/cshaun/tensorflow-intro.git tensorflow-intro.git
$ cd ./tensorflow-intro.git
```

Then create a virtual environment and setup your environment:

```bash
$ python -m virtualenv --no-site-packages --distribute env
$ source env/bin/activate
(env) $ pip install -U git+https://github.com/MonashDataFluency/intro-to-tensorflow.git
(env) $ pip install jupyter
```

This installs the Monash DataFluency `TutorialSupport` package and dependencies, including `TensorFlow` and some sample datasets for machine learning.

To start the Jupyter notebook server:

```bash
(env) $ jupyter notebook
```
which should launch your browser, displaying the Jupyter dashboard and the contents of the current directory.
