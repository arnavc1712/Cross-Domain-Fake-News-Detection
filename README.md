# Cross-Domain-Fake-News-Detection
Built a domain independent Multi Task and End to End Deep Learning model which can be trained on one news domain to classify fake news, and be used to classify fake news on another domain.

Multiple models were built and tested, and this notebook as well as the report attached takes you through the whole process. Enjoy!

Inspired from this paper by Microsoft - https://www.microsoft.com/en-us/research/publication/domain-adaptation-for-commitment-detection-in-email/

We tried to answer the following questions:
1. Can fake news be detected?
2. How does the performance of fake news detection models change when they are tested on a domain different from the one on which it was trained?
3. How do we characterize differences between domains,
and how do we transfer knowledge learned from one
domain to apply to another domain?
4. Does including the proposed auto-encoder in our model,
help to improve classification accuracy?

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run
```bash
jupyter notebook Cross_Domain_Fake_News.ipynb
```
