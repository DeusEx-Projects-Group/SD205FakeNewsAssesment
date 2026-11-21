# SD205 Fake News Assessment

Fake News Detection MVP developed for SD205 Assessment 2.

This repository contains the completed end-to-end application together with a filtered branch showing my individual contribution.

## Repository Structure

The repository uses two branches to separate the completed product from individual contribution evidence.

### `main`

The `main` branch contains the completed end-to-end application:

- WELFake data preparation
- TF-IDF feature extraction
- Logistic Regression classification
- Final trained ML pipeline
- Flask application and API
- Model-service integration
- Integrated frontend
- Confidence-threshold audit
- Three-state interpretation policy
- Automated tests
- Project documentation

### `james-integration`

The filtered branch contains the work attributable to my specialist contribution:

- Flask application factory
- Backend-to-frontend integration
- Model-service boundary
- Model SHA-256 verification
- Health and prediction endpoints
- Request validation
- Structured API responses
- Integrated testing frontend
- CSS and JavaScript
- Confidence-threshold audit
- Runtime interpretation policy
- Integration and frontend tests

The machine-learning development direction, including WELFake, TF-IDF and Logistic Regression, represents Victor's specialist contribution.

My responsibility was integrating the exported machine-learning pipeline into a controlled Flask runtime and creating the frontend used to operate, test and demonstrate the complete application.

## Project Objective

The application accepts:

- a news headline;
- article text;
- or both together.

The submitted text is 
