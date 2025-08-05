# Customer Feedback Cleaner (Basic NLP Project)

A simple NLP pipeline that cleans messy customer feedback by removing duplicates, punctuation, casing issues, and spacing problems. Perfect starting point for real-world text preprocessing in Python

---

## Project Description

This project takes messy, inconsistent customer feedback data and transforms it into clean, readable text. It removes:
- Duplicates
- Punctuation
- Irregular spacing
- Uppercase letters
- Missing entries

The output is a cleaned CSV file with one feedback column ready for text analysis or NLP projects.

---

## Dataset Example (Before Cleaning)

| Feedback                                 |
|------------------------------------------|
| I loved the product!!! 😍😍              |
| BAD service... never again :(            |
| Good quality - fast delivery.            |
| Excellent service, will buy again!       |
| good quality - fast delivery.            |
| This is the WORST experience EVER!! 🤢   |

---

## Output Example (After Cleaning)

| CleanedFeedback                |
|-------------------------------|
| i loved the product           |
| bad service never again       |
| good quality fast delivery    |
| excellent service will buy again |
| this is the worst experience ever |

---

## Tools & Libraries

- Python 3
- Pandas
- Regular Expressions (`re`)
- Jupyter Notebook (optional)

---

## How to Run

1. Clone the repo or copy the files locally.
2. Install dependencies:
```bash
pip install -r requirements.txt
