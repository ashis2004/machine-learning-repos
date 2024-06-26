# Resume Selection System

This project implements a resume selection system using machine learning techniques for classification.

## Overview

The system uses natural language processing (NLP) to analyze resume texts and classify them into two categories:
- 'flagged': Resumes that meet certain criteria (e.g., relevant skills, experience).
- 'not_flagged': Resumes that do not meet the criteria.

The system utilizes the following machine learning algorithms:
- CountVectorizer for text preprocessing.
- Multinomial Naive Bayes for classification.
- Other classifiers (SVM, Logistic Regression, etc.) can be implemented and evaluated.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/resume_selection_system.git
   cd resume_selection_system
