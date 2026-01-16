# Project Title
Customer Support Message Labeling

## Project Description
This project involves labeling a dataset of short customer support messages with intent, sentiment, and PII flags to help train AI models for automated support.

## Purpose of the Dataset
- Train AI systems to understand customer intent and sentiment.
- Identify sensitive information for privacy protection.
- Evaluate automated support solutions.

## How Labels Were Applied
| Message                              | Intent   | Sentiment | PII Flag |
|--------------------------------------|---------|----------|----------|
| “I can’t log in to my account.”      | Complaint | Negative | No       |
| “Thanks for the quick response!”     | Feedback  | Positive | No       |
| “My email is xyz@example.com”         | Request   | Neutral  | Yes      |

## Guidelines for Future Users
- Check the **context** of the message before labeling.
- Be consistent with sentiment labeling.
- Flag any personal information (emails, phone numbers, etc.).
- When unsure, mark for **review** rather than guessing.

## Optional: Sample Rows
