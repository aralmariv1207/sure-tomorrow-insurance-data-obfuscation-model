# Sure Tomorrow: Insurance Data Obfuscation

## About

Explores the intersection of data privacy and machine learning. Protects client personal data for the Sure Tomorrow insurance company. Developed as a mathematical masking algorithm that transforms sensitive features so they are unreadable to unauthorized users, while proving that the transformation does not impact the predictive quality of machine learning models.

## Technical Highlights

· **Customer Similarity**: Implemented a **K-Nearest Neighbors (KNN)** algorithm to identify customers similar to a specific profile, comparing results between scaled and unscaled data.

· **Benefit Prediction**: Built and evaluated a classification model to predict whether a new client is likely to receive an insurance benefit.

· **Linear Algebra Implementation**: Developed a custom **Linear Regression** model using matrix operations to predict the number of insurance benefits a client might receive.

· **Obfuscation Proof**: Programmed a data masking algorithm using an invertible matrix ($P$) to obfuscate features ($X$) into $X' = XP$.

· **Evaluation**: Verified that the **RMSE** and $R^2$ metrics remained identical for both original and obfuscated datasets, confirming the mathematical integrity of the transformation.
