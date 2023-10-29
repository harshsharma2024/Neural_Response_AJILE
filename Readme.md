
Neural Response and Body Movements Linking Project

Questions:
What are the patterns of neural activity that best correspond to each task?


How does the brain differentiate the information from one task to another?


This project aims to explore the relationship between neural responses and body movements using the AJILE dataset. The AJILE dataset contains a collection of neural recordings and corresponding body movement data, providing a valuable resource for investigating the neural basis of movement.

Exploring tasks according to groups of electrodes showing strongest signal.


PREPROCESSING:
Data extraction from DANDI per task (timesteps process)
Removal of bad channels according to the table
Band pass filter (1-100 Hz)

Feature extraction from ECoG data:
Average the spectral power (composite Simpson's rule) for the band Beta (12-30 Hz) for epoch of 5 seconds

Dimensionality reduction: Principal Component Analysis
Model: Logistic Regression

This project demonstrates the process of linking neural responses with body movements using the AJILE dataset. The findings and insights gained from this analysis contribute to our understanding of the neural basis of movement.

For any questions or further information, please contact [Harsh Sharma] at [harshsharma2024@gmail.com].
