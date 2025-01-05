TikTok Video Classification Project
Overview

This project uses machine learning to classify TikTok videos as either "claims" or "opinions," helping TikTok efficiently identify videos that might violate the platform’s terms of service.
Objective

The goal is to build a model that predicts whether a TikTok video is a claim or an opinion. This helps prioritize videos for human review, ensuring terms of service violations are addressed swiftly.
Approach

The project follows the PACE framework:

    Plan: Define the business problem and objectives.
    Analyze: Explore and preprocess the data.
    Construct: Build the machine learning model.
    Execute: Deploy the model.

Target Variable

The model predicts claim_status, a binary variable indicating whether a video is a claim or an opinion.
Evaluation Metric

The evaluation metric is recall, as it's more important to minimize false negatives (claims classified as opinions) than false positives. False negatives risk missing harmful content.
Ethical Considerations

The model focuses on reducing false negatives, ensuring that videos violating TikTok’s terms are flagged for review, even if some opinion videos are misclassified as claims.
Conclusion

This model automates the classification of TikTok videos, helping prioritize claims for review and improving moderation efficiency. The model’s focus on recall ensures important content isn’t overlooked.
