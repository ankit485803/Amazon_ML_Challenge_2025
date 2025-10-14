

# ML Challenge 2025 - Smart Product Pricing Challenge

## Problem Overview
Your challenge is to develop a machine learning model to predict the optimal price of a product based on its details such as title, description, and image. The relationship between product attributes and pricing is complex, and your task is to build a model that analyzes these attributes and suggests an optimal price.

## Data Description
The dataset contains the following columns:
1. **sample_id**: Unique identifier for the product.
2. **catalog_content**: Text containing title, description, and Item Pack Quantity (IPQ).
3. **image_link**: URL to the product image (used for image-based features).
4. **price**: Price of the product (only in training data).

### Dataset Files:
- **train.csv**: Training data with labels (price).
- **test.csv**: Test data without labels (price).
- **sample_test.csv**: Sample test input file.
- **sample_test_out.csv**: Sample output format.

## Task
- Predict the price for the test dataset.
- Output the predictions in a CSV file with two columns: `sample_id` and `price`.

## Output Format
```csv
sample_id, price
12345, 49.99
23456, 89.99
...
