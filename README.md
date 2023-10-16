# Readme
This repository contains a collection of CloudFormation samples highlighting the different functionalities AWS CloudFormation has to offer.

# Deploying AWS CloudFormation Template from GitHub Repository

This guide provides step-by-step instructions on deploying an AWS CloudFormation template from your GitHub repository. AWS CloudFormation is a service that allows you to define and provision AWS infrastructure as code.

## Prerequisites

Before you begin, make sure you have the following prerequisites:

- An **AWS account**: You need an AWS account with appropriate permissions to create AWS resources.
- A clonse of this **GitHub repository**

## Step 1: Clone the GitHub Repository

To get started, clone the GitHub repository to your local machine using Git.

Open your terminal or command prompt and run:

```bash
git clone git@github.com:mbloch1986/cloudformation-samples.git
```
## Step 2: Access AWS CloudFormation

1. Sign in to the [AWS Management Console](https://aws.amazon.com/console/).
2. Navigate to the AWS CloudFormation service.

## Step 3: Create a New Stack

1. Click the "Create stack" button.
2. Choose "With new resources (standard)" and click "Next."

## Step 4: Specify Stack Details

Fill in the stack details:

- **Stack name**: Provide a unique name for your stack.
- **Parameters**: Configure any required parameters according to your CloudFormation template.
- **Tags**: Optionally, add tags for your resources.

Click "Next" to proceed.

## Step 5: Configure Stack Options

You can configure advanced options here, such as stack policies, permissions, and notification settings. Adjust these settings as needed and click "Next."

## Step 6: Review and Create

Review your stack configuration, and if everything looks correct, click "Create stack."

## Step 7: Monitor Stack Creation

AWS CloudFormation will start creating the stack and its resources. You can monitor the progress in the AWS CloudFormation console.

## Step 8: Stack Deployment Complete

Once the stack deployment is complete, you can access the resources created by your CloudFormation template.


# Testing AWS CloudFormation Template with AWS TaskCat

This documentation provides a step-by-step guide on how to test an AWS CloudFormation template using AWS TaskCat. AWS TaskCat is a tool that helps automate testing of CloudFormation templates for AWS resources, ensuring that your infrastructure is reliable and functions as expected.

## Prerequisites

Before you begin testing your CloudFormation template with AWS TaskCat, make sure you have the following prerequisites in place:

- **AWS Account**: You should have an AWS account with the necessary permissions to create CloudFormation stacks.
- **Python Installed**: Ensure Python is installed on your local machine.
- **AWS CLI Installed**: Install the AWS Command Line Interface (CLI) on your machine.
- **AWS Credentials**: Set up AWS credentials on your machine using the `aws configure` command.

## Step 1: Install AWS TaskCat

1. Open your terminal or command prompt.

2. Install AWS TaskCat using pip:

   ```bash
   pip install taskcat

   ```

## Step 2: Run Tests with TaskCat


1. Open your terminal or command prompt.

2. Configure AWS CLI credentials

  ```bash
  aws configure
  ```

3. Run all test cases:

   ```bash
   taskcat test run

   ```
