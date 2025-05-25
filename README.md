##Transformer Health Monitoring System

The Transformer Health Monitoring System is a data-driven solution developed to support predictive maintenance of power transformers using machine learning techniques. Transformers are critical components in the electrical power grid, and their unexpected failure can lead to significant operational downtime and financial losses. Traditional maintenance methods often rely on periodic inspections, which may fail to detect early signs of internal deterioration.

This project aims to automate and enhance the process of transformer health evaluation by analyzing Dissolved Gas Analysis (DGA) and oil test parameters. These parameters are key indicators of transformer condition, often revealing insulation breakdown, overheating, and other internal faults.

##Key Features

#Machine Learning-Based Classification
Utilizes a Random Forest classifier to categorize transformer health into five levels: Very Good, Good, Fair, Poor, and Very Poor.

#Data Imbalance Handling
Applies the Synthetic Minority Oversampling Technique (SMOTE) to balance the dataset and improve the model’s performance across all health categories.

#User-Friendly Web Interface
Integrates a Gradio-based web application that allows users to input test results and receive real-time health predictions, potential fault diagnostics, and preventive maintenance suggestions.

#Real-World Application
Designed for deployment in power stations, substations, and industrial environments where efficient, reliable transformer monitoring is essential.

##Objectives
Develop a robust machine learning model to classify transformer health based on real diagnostic parameters.

Convert complex numerical data into simple, understandable labels to aid quick decision-making.

Enhance prediction accuracy and reduce bias using SMOTE for class balancing.

Provide a clean and interactive user interface for non-technical stakeholders to use the system with ease.

Offer actionable suggestions based on the predicted condition to support preventive maintenance strategies.

##Technologies used
Programming Language: Python

Libraries and Tools:

Pandas and NumPy for data handling

Scikit-learn for model building

Imbalanced-learn (SMOTE) for data balancing

Gradio for web interface

Google Colab for development and deployment

##Outcome

The final system delivers a reliable, efficient, and accessible method for monitoring transformer health. By combining machine learning with an intuitive interface, it empowers maintenance teams to act on early warnings, extend transformer lifespan, and ensure uninterrupted power delivery. The approach offers a scalable foundation for integration with smart grid technologies and future enhancements involving real-time sensor data.
