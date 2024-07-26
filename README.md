# Build_ML_Workfload_on_SageMaker

# Project Overview

The aims of the project is to  build an image classification model that can automatically detect which kind of vehicle delivery drivers have, in order to route them to the correct loading bay and orders. Assigning delivery professionals who have a bicycle to nearby orders and giving motorcyclists orders that are farther can help Scones Unlimited optimize their operations.

In this project, We used AWS Sagemaker to build an image classification model that can tell bicycles apart from motorcycles. We deployed our model, used AWS Lambda functions to build supporting services, and AWS Step Functions to compose our model and services into an event-driven application.

# Project Steps Overview

Step 1: Data staging

Step 2: Model training and deployment

Step 3: Lambdas and step function workflow

Step 4: Testing and evaluation

# Running the Project

Once you open the AWS Console, navigate to the main Sagemaker page and open up Sagemaker Studio. When your Sagemaker Studio instance is running, be sure to git clone the repository . Navigate to the "project_starter" folder which contains the starter notebook starter.ipynb.
