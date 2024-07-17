## Agents for Amazon Bedrock Feature Samples

This repository contains Jupyter notebooks demonstrating the use of Amazon Bedrock Agents. These notebooks correspond to YouTube videos and blogs that explain and showcase different features of Amazon Bedrock Agents.

## Notebooks

1. `preview-agent-code-interpreter.ipynb`: Demonstrates how to set up and use an Amazon Bedrock Agent with Code Interpreter capabilities.
2. `preview-agent-long-memory.ipynb`: Shows how to create an Amazon Bedrock Agent with long-term memory functionality.

## Features Demonstrated

### Code Interpreter Agent
- Setting up an AWS Bedrock Agent with Code Interpreter
- Configuring the agent to use Claude 3 Sonnet as the foundation model
- Interacting with the agent to perform tasks like:
  - Calculating Fibonacci sequences
  - Plotting graphs
  - Analyzing and visualizing sample data

### Long-Term Memory Agent
- Creating an AWS Bedrock Agent with long-term memory capabilities
- Using Claude 3 Haiku as the foundation model
- Demonstrating how the agent retains information across multiple chat sessions

## Prerequisites

- AWS account with access to Amazon Bedrock
- Python 3.x
- Jupyter Notebook
- Required Python libraries: boto3==1.34.144, matplotlib

## Setup

1. Clone this repository
2. Install the required Python libraries
3. Set up your AWS credentials
4. Open the notebooks in Jupyter and follow the instructions within

## Usage

Each notebook contains step-by-step instructions for creating, interacting with, and cleaning up the Bedrock Agents. They include explanations of the code and concepts, making them suitable for both learning and experimentation.

## Important Notes

- These notebooks use features that may be in preview at the time of creation. Check the current status of Amazon Bedrock features before use.
- Remember to run the cleanup cells at the end of each notebook to remove created resources and avoid unnecessary charges.

## Disclaimer

The code in this repository is for demonstration purposes. Ensure you understand the AWS pricing for Bedrock and related services before running these notebooks in your own environment.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

