# Scones Unlimited: Image Classification Project

## Overview

Welcome to the **Scones Unlimited** image classification project! As a Machine Learning Engineer for Scones Unlimited, your goal is to develop a scalable and robust image classification model using AWS services. This model will help the company optimize their logistics operations by identifying delivery vehicles (bicycles vs. motorcycles) from images. With this capability, Scones Unlimited can better route orders to the appropriate delivery drivers, enhancing efficiency and customer satisfaction.

## Project Objectives

1. **Data Staging**: Prepare and stage the data required for training the image classification model.
2. **Model Training and Deployment**: Train an image classification model using AWS SageMaker and deploy it for inference.
3. **Lambdas and Step Function Workflow**: Create AWS Lambda functions and compose them into a Step Function workflow to handle model inference and additional tasks.
4. **Testing and Evaluation**: Evaluate the model's performance and ensure it meets the desired accuracy and reliability standards.
5. **Cleanup**: Properly clean up all cloud resources to avoid unnecessary charges.

## Project Structure

- **Step 1: Data Staging**
  - In this step, you'll gather, clean, and prepare the dataset required for training the model. This may involve using AWS S3 to store and manage your data.
  
- **Step 2: Model Training and Deployment**
  - You'll use AWS SageMaker to build, train, and deploy an image classification model. This model will be trained to distinguish between bicycles and motorcycles, which will be crucial for the company's logistics operations.
  
- **Step 3: Lambdas and Step Function Workflow**
  - Develop AWS Lambda functions that will support the model's deployment. You'll also create an AWS Step Function workflow to orchestrate the entire process, ensuring that the model is invoked efficiently and at the right time.
  
- **Step 4: Testing and Evaluation**
  - Test the deployed model using various images to evaluate its performance. You'll check for accuracy, scalability, and robustness. This step also involves setting up monitoring and alerting mechanisms to detect model drift or performance degradation.
  
- **Step 5: Cleanup Cloud Resources**
  - After completing the project, it's important to clean up all the AWS resources to avoid incurring unnecessary costs. This includes terminating SageMaker endpoints, deleting S3 buckets, and removing Lambda functions.

## Technologies Used

- **AWS SageMaker**: For training and deploying the image classification model.
- **AWS Lambda**: To create serverless functions that handle inference and support the Step Function workflow.
- **AWS Step Functions**: To orchestrate the entire workflow, ensuring that the right processes are triggered at the right time.
- **AWS S3**: To store and manage the dataset used for training the model.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:

- An AWS account with sufficient permissions to use SageMaker, Lambda, Step Functions, and S3.
- Familiarity with Python programming and basic Machine Learning concepts.
- Knowledge of AWS services, particularly SageMaker, Lambda, and Step Functions.

### Installation and Setup

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/abrhamgg/ML-Workflow-For-Scones-Unlimited.git
