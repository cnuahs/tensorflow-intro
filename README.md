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
$ python3 -m virtualenv --no-site-packages --distribute env36
$ source env/bin/activate
(env36) $ pip3 install -U git+https://github.com/MonashDataFluency/intro-to-tensorflow.git
(env36) $ pip3 install jupyter
```

This installs the Monash DataFluency `TutorialSupport` package and dependencies, including `TensorFlow` and some sample datasets for machine learning. Note that the `TutorialSupport` package resets the random seed each time a session is created, to ensure results are reproducible, and limits the number of threads to 2. The `TutorialSupport` package requires python3 (tested using python3.6 on OS X).

To start the Jupyter notebook server:

```bash
(env) $ jupyter notebook
```
which should launch your browser, displaying the Jupyter dashboard and the contents of the current directory.

---

Alternatively, you can probably open the notebook on [Google's Colaboratory](https://colab.research.google.com/ "Google Colab") by clicking this button: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cnuahs/tensorflow-intro/blob/master/ML_Coursework_Student.ipynb).

To run on Colab you need to install the `TutorialSupport` package from within the notebook by adding and executing a code cell containing something like:

```
pip install git+https://github.com/MonashDataFluency/intro-to-tensorflow.git
```
