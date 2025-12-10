# HR NLP Toolkit – Employee Feedback Analysis

This project provides an end-to-end Natural Language Processing (NLP) pipeline designed for Human Resources (HR) analytics, focusing on analyzing employee feedback using modern transformer-based models.

It performs multiple HR-relevant tasks, including:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Sentiment Analysis</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Burnout / Stress Detection</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Topic Modeling</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Summarization</span>


HR Recommendation Tags Extraction

The toolkit helps HR teams quickly understand employee concerns, identify areas of improvement, and generate actionable insights from raw textual feedback.

🚀 Features
1. Sentiment Analysis

Uses state-of-the-art transformer models to classify employee feedback into:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Positive</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Negative</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Neutral</span>

Useful for measuring general employee satisfaction and detecting critical feedback.

2. Burnout / Stress Detection

This module applies a classification model to detect:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Stress signals</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Burnout symptoms</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Emotional exhaustion patterns</span>

Helpful for early intervention and improving employee well-being.

3. Topic Extraction (LDA / BERTopic)

Automatically clusters feedback into key themes.
Examples:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Management issues</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Workload</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Compensation</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Work environment</span>

Supports:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">LDA (Latent Dirichlet Allocation)</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">BERTopic (Transformers + clustering)</span>



4. Summarization

Generates short, meaningful summaries from long feedback text using transformer summarization pipelines.
Ideal for HR reports, dashboards, and executive summaries.

5. HR Recommendation Tags

Automatically assigns HR-related tags such as:

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Training Needed</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Low Morale</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Team Conflict</span>

<span style="height: 20px; width: 20px; background-color: #bbb; border-radius: 50%; display: inline-block;">Workload Concern</span>

Enables fast prioritization and categorization.
