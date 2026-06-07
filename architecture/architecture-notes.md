# Architecture Notes

## Data Flow

External API
→ AWS Lambda
→ Amazon S3
→ AWS Glue Crawler
→ AWS Glue Data Catalog
→ Amazon Athena
→ Business Insights

## Description

This project uses AWS Lambda to extract sales data from an external API, perform data cleaning and transformation using Python and Pandas, store processed data in Amazon S3, catalog metadata using AWS Glue Crawler, and query datasets using Amazon Athena.
