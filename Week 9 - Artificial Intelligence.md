# Week 9 - Artificial Intelligence

## What is Artificial Intelligence (AI)?
- Russell & Norvig (2010) define AI in four ways:
    - Machines that think like humans
    - Machines that act like humans
    - Machines that think rationally
    - Machines that act rationally

- the study of AI is the study of "intelligent agents" - any device that perceives its environment and takes actions that maximise its chance of successfully achieving its goals

## How can AI be biased?
1. Reporting Bias
    - occurs when certain information is overrepresented or underrepresented in the training data, leading to skewed outcomes. For example, if a facial recognition system is trained primarily on images of light-skinned individuals, it may perform poorly on darker-skinned individuals due to the lack of diverse representation in the training set.

2. Historical Bias
    - arises from existing societal biases that are reflected in the training data. For instance, if a hiring algorithm is trained on historical hiring data that reflects past discrimination, it may perpetuate those biases in its decision-making.

3. Automation Bias
    - is the tendency to over-rely on automated systems, leading to errors when the system makes mistakes. For example, if a medical diagnosis AI suggests a treatment plan, doctors may be inclined to follow it without question, even if it is incorrect, potentially leading to adverse patient outcomes.

4. Selection Bias
    - occurs when the data used to train an AI model is not representative of the population it will be applied to. For example, if a loan approval AI is trained on data from a specific geographic region, it may not perform well when applied to applicants from different regions with varying economic conditions.

5. Group Attribution Bias
    - is the tendency to assume that individuals within a group share the same characteristics or behaviors. For example, if an AI system is trained on data that associates certain behaviors with a specific demographic group, it may unfairly generalize those behaviors to all members of that group, leading to discriminatory outcomes.

6. Implicit Bias
    - refers to the unconscious attitudes or stereotypes that can influence decision-making. For example, if an AI system is trained on data that reflects societal biases

7. Confirmation Bias
    - is the tendency to search for, interpret, and remember information in a way that confirms one's preexisting beliefs. For example, if an AI system is designed to identify potential threats based on certain characteristics, it may disproportionately flag individuals who fit a stereotypical profile, reinforcing existing prejudices.

8. Experimenter's Bias
    - occurs when a researcher's expectations or preferences influence the outcome of an experiment. In the context of AI, this can happen if developers unintentionally design algorithms or select data in a way that aligns with their beliefs, leading to biased results.

### Mitigating AI Bias
- Pre-Processing
    - consultation and community engagement, data cleaning, re-sampling, and augmentation

- In-Processing
    - fairness-aware algorithms and modifications during training

- Post-Processing
    - adjustments to model outputs

### Detecting AI Bias
- EDA
    - checks for missing or unexpected data; evaluate data skew

- Formal Statistical Evaluation
    - fairness metrics (e.g., demographic parity, equal opportunity)

- Visualisation Tools
    - fairness dashboards and confusion matrices

## Defining Ethical Use of Ai

### Detecting AI-generated Content
- ethical issues in AI-generated content include:
    - image-based abuse
    - fake news and misinformation
    - AI cheating in education

- detection methods:
    - linguistic analysis
    - metadata analysis
    - statistical methods
    - machine learning models and detection software

