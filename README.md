# MLOps_Amazon-Sagemaker_MNIST
 CI/CD using AWS Sagemaker to Image Recognition using MNIST

infra: contains CloudFormation template pipeline.yml, that you will use to create your CI/CD pipeline

source: contains the code that will be used to train and test your model

lambda: contains a Lambda function that can query the endpoint of your model