# Hands-On 03

This session focuses on building a complete Customer Review Sentiment Analysis system with alerting capabilities.

## Workflows

### HO3_Customer_Review_Sentiment_Classification.json
The main workflow that:
1.  Ingests customer reviews.
2.  Classifies them by sentiment (Positive, Neural, Negative).
3.  Identifies the motive/reason for the sentiment.

### HO3_AI_Sentiment_Analysis.json
Likely an alternative or sub-component for the sentiment analysis logic, possibly using a different model or prompt structure for comparison.

### HO3_Send_Email_Alert.json
A dedicated sub-workflow or connected component that handles sending email notifications when specific criteria are met (e.g., a Negative review is detected).
