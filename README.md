# Hands-On-ML-Journey
My ML Journey from following along ML projects to actually understanding the behind the scenes.

### Learning ML (The Hard Way)

I've already built some projects like Diabetes Predictor, Sales Predictor and some more by following tutorials and using Colab. **The truth?** Sometimes I was just copying code without fully getting *why* it worked.

So to fix this I’m using Aurélien Géron's book to just stop "following along" and start "knowing." This repo is my brain dump.

### What’s happening here:
- **Notebooks:** My messy attempts at the book's exercises.
- **Notes:** Explanations for my future self so I don't forget.
- **Mistakes:** A list of things I broke and (hopefully) fixed.

### The Goal:
Just get through the book, one chapter at a time, and get better at Python and ML logic.

## Learning Roadmap

| Chapter | Project / Topic | Status | Key Mastery |
| :--- | :--- | :--- | :--- |
| **01** | The ML Landscape | ✅ Complete | Overfitting vs. Underfitting, Model Selection |
| **02** | California Housing | ✅ Complete | Pipelines, Stratified Sampling, Custom Transformers, Cross-Validation |
| **03** | MNIST | ✅ Complete | Classification, Precision, Recall, Tradeoff, F1-score |
| **04** | Training Models | ✅ Complete | Gradient Descent and types, MSE, Normal Equation, Regularization
| **05** | SVM | 🚀 In-Progress |
## My Learn Log
Jan 01 2026: Chapter-02 lessons
1. This chapter made me realize the actual importance of data preprocessing and that I will maximum time doing it in a project.
2. The importance of Stratified Sampling and how it averts sampling bias, keeping the distribution even.
3. It is taking me some while to understand the data pipline and Custom Transformer part. *Update*: I understand it now!!
4. (**Jan 05 2026**) CustomTransformers and Pipelines are a Godsend!! They literally almost automate the whole process!!
Jan 05 2026:
My Breakthrough:
>"Until the 4th exercise, every change was split and manual. This exercise forced me to actually integrate it all: scaling, imputation, encoding, and custom transformers into a single Pipeline. This was the moment where the logic of CustomTransformers and Pipelines finally clicked."

Jan 09 2026: Chapter-03 lessons
1. The Classification shift was real! It was very different from predicting singular values.
2. Understanding that sometimes accuracy can be misleading was certainly a boon. Otherwise I would have been trapped thinking my model was performing perfectly.
3. Learned better metrics in the form of Precision, Accuracy, their relationship and f1_score. *f1_score helped me a lot in the exercises*
4. Understood Confusion Matrix properly with the help of MNIST dataset.
5. The proper format of pipelines and CustomTransformers, along with various models was understood.

*Tools update*:
1. I transitioned from using colab to *Jupyter Notebooks*.
2. Understood the importance and creation of virtual environments.
My Breakthrough:
>"My real breakthrough happened in the form of proper understanding of pipelines and structure. Not only that uderstanding how different models perform on a single dataset and the help of f1_score in understanding that."

Jan 15 2026: Chapter-04 lessons

1. I actually understood what happens when `fit()` is called. **Normal Equation** and **Gradient Descent** showed me how the model actually "walks" toward the best parameters.
2. I learned the differences and trade-offs between **Batch GD** (stable but slow), **Stochastic GD** (fast but jumpy), and **Mini-batch GD** (the perfect middle ground).
3. Using **Learning Curves** helped me visualize how **Overfitting** and **Underfitting** actually differ.
4. I got to know about **Regularization**. How adding a penalty to the cost function is really useful for keeping models from getting too complex.
5. I realized that even if data is non-linear, I can still use linear models by adding higher-degree features to my **Pipeline**.

### **My Breakthrough:**

> "I used to think of models as "Machines". This chapter forced me to see the math. The cost function being the 'mountain' and Gradient Descent the 'path down.' Learning about **Early Stopping** was the highlight—it's like having an automated 'Stop' button the second the model starts overfitting, saving time and computation."





---
*If you're also learning this, feel free to point out if I'm doing something wrong!*

**How to use:** Since I'm learning on the go, I use Google Colab. *Update*: I started using Jupyter Notebooks
