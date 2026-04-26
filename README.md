# **IMCS3010U Project: Textual/Binary Classification of Math Vs. Non-Math Textual Content**

## **Table of Contents**
- [***Project Information***](#project-information)
- [***Getting Started***](#getting-started)
- [***Project Testing Results***](#project-testing-results)
- [***Author(s)***](#authors)

## **Project Information**

### **Overview**
This project was developed as a chosen topical project for the **IMCS3010U: Integrated Project Course I** during the 2025 Fall Semester at Ontario Tech University. Its main purpose is to determine whether a computer is able to differentiate between math and non-math textual content containing shared terms.


### **Description**
It is no surprise that mathematical linguistics is considered a universal language that transcends global borders. However, one of the most fascinating aspects of this language is the existence of shared terms with other standardized languages that contain completely different definitions and interpretations depending on how it is used and the verbal and textual context surrounding its usage. This discovery raised an important question: “Is a computer able to computationally differentiate between a mathematical and non-mathematical piece of text containing shared terms, and if so, is there a variety of analytical steps and methodologies to showcase that this is a possibility?” This question resulted in the primary research topic for this project, which is the **Textual/Binary Classification of Math vs. Non-Math Textual Content**.

<img width="561" height="587" alt="image" src="https://github.com/user-attachments/assets/ecfb905c-2cbd-4167-853f-c2d4a937bfde" />


### **Project Contributor(s)**
- **Tobenna Nnaobi**

## **Getting Started**

### **Requirements**
- Any Version $\leq$ **Python 3.12.10** Is Required
- Any IDE With Jupyter Notebook Is Recommended (e.g. **Visual Studio Code**) 

### **Dependencies & Modules**
- **NLTK**: Also known as Natural Language Toolkit, it is considered a leading platform for
building Python programs to work with human language data. It provides easy-to-use cor-
pora and lexical resources such as WordNet, along with a suite of text processing libraries
for classification, tokenization, stemming, tagging, parsing, and semantic reasoning.
    - **nltk.text.concordance**: In data visualization, it is a dependency derived from the nltk.text 
    module, used to computationally visualize the contextual use cases of specified word or
    *”term”*.

- **PyLaTeXEnc**: A Python resource that can convert Unicode text to LaTeX code and vice
versa. It also provides functions for parsing LaTeX code and converting it into plain
text via its latex2text dependency.

- **Pandas**: A fast, powerful, and flexible Python dependency that used for primarily for data analysis and manipulation purposes.
    - **pd.DataFrame**: A module capabale of creating a two-dimensional, size-mutable, potentially heterogeneous tabular dataset using a fixed set of data.

- **Scikit-Learn**: A Python module that is utilized for machine learning purposes and contains
tools for predictive data analysis. It is built on NumPy, SciPy, and matplotlib.
    - **sklearn.metrics.pairwise.cosine similarity**: A type of metric utilized to compute the cosine
    similarity between two samples in X and Y.

- **Matplotlib**: A powerful Python dependency that used to display graphical representations
of pieces of critical data.
    - **matplotlib.pyplot**: A state-based interface to matplotlib. It provides an implicit, MATLAB-
    like, way of plotting graphical representations. pyplot is mainly intended for interactive
    plots and simple cases of programmatic plot generation.

- **TensorFlow**: A free open-source dependency in Python developed by the now defunct
Google Brain. It is usually used for computational development specifically within the
realm of machine-learning and artificial intelligence (AI).
    - **tf.keras.Sequential**: A dependency that is used to group a linear stack of layers into an
    RNN Model.
    - **tf.keras.layers**: A dependency that is used to provide a list of fundamental building com-
    ponents of a recurrent neural network.
    - **tf.keras.preprocessing.text.Tokenizer**: A dependency used to initialize a tokenizer that
    will transform a textual dataset into a padded sequence of numbers.


## **Project Testing Results**

<img width="825" height="421" alt="image" src="https://github.com/user-attachments/assets/635d33ee-9109-4fad-a925-97a1eb9e4819" />


## **Author(s)**
- **Tobenna Nnaobi**






