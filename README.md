# Kidney Disease Classification with MLflow and DVC

![image](https://github.com/user-attachments/assets/a2fecd60-f56d-41f4-bbb3-2ece89c7e19b)

## Project Overview

The **Kidney Disease Classification** project is an end-to-end machine learning solution aimed at diagnosing kidney disease based on clinical data. By utilizing MLflow for experiment tracking and DVC for data version control, the project ensures that each step of the machine learning workflow is reproducible, manageable, and efficient.

The model employs VGG16 model to classify kidney health, enabling healthcare professionals to make informed decisions based on predictive analytics. The integration of MLflow facilitates the tracking of experiments, allowing for better model management and versioning. DVC, on the other hand, provides robust data handling capabilities, ensuring data integrity and traceability throughout the lifecycle of the project.

## Pipeline Steps

The project's workflow is organized into several key components:

1. **Configuration Management**: Centralized management of configurations via `config.yaml`, `secrets.yaml`, and `params.yaml` to easily adjust project parameters and sensitive information.

2. **Entity and Component Updates**: Regular updates to the entities and components involved in the classification process to reflect any changes in the data or model architecture.

3. **Pipeline Development**: Building and refining the machine learning pipeline, ensuring all steps from data preprocessing to model training and evaluation are systematically organized.

4. **Experiment Tracking**: Leveraging MLflow to log experiments, track parameters, and manage models effectively.

5. **Data Version Control**: Using DVC to ensure data versions are managed properly, allowing for reproducibility and tracking of changes to datasets throughout the project.

6. **Deployment**: Preparing the model for deployment, enabling it to be utilized in real-world applications, ensuring accessibility for healthcare practitioners.

This structured approach ensures that the project is not only focused on achieving high accuracy in predictions but also emphasizes the importance of maintainability and scalability in machine learning projects.
