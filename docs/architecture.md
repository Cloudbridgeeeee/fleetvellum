# Proposed AWS architecture

| Service | Role |
|---|---|
| S3 | Encrypted invoice scans and mileage exports per customer |
| Textract | Line items, amounts and plate numbers read from invoices |
| SageMaker AI | Cost classification, forecasts and discrepancy scoring |
| Bedrock and DynamoDB | Plain-language alert notes; vehicles, costs and the review log |

One AWS account per customer, encrypted at rest and in transit. The public demo calls none of these services.
