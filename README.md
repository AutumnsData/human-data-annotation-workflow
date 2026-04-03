# Human Data Annotation Workflow – Sentiment Analysis for AI Training

## Project Overview
I designed and executed a human data annotation pipeline using Label Studio to create labeled data for training AI sentiment models. The goal was to turn raw customer reviews into high-quality training examples.

## Dataset
- 20 Amazon-style product reviews stored in sample_reviews_fixed.csv
- Each review labeled as Positive, Negative, or Neutral

## Annotation Instructions I Created
- Positive: Clear praise, enthusiasm, or recommendation
- Negative: Complaints, disappointment, or criticism
- Neutral: Facts without strong opinion
- Kept guidelines short and clear so any annotator could stay consistent

## What I Did
- Imported the CSV as a list of tasks
- Labeled 15+ reviews myself
- Exported the labeled data as CSV

## Quality Control & KPIs
- Worked as a single annotator so no agreement conflicts
- Completed labeling quickly with attention to consistent rules
- In a real team workflow I would track: labels per hour, inter-annotator agreement, and spot-check accuracy

## Scaling & Automation Ideas
- Add multiple annotators and use Label Studio's agreement scoring
- Pre-label uncertain reviews with a simple Python model, then have humans review only those
- Export automatically to a database or cloud storage for larger projects

## Files
- sample_reviews_fixed.csv (raw data)
- labeled_reviews.csv (after annotation)
- Project created in Label Studio (Text Classification template)

This project shows practical experience setting up human data workflows for AI training — directly relevant to data operations and annotation roles.