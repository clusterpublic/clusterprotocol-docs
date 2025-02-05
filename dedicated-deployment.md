# Dedicated deployment

## Cluster Protocol Deployment Documentation

### Overview

The Deployment page on the Cluster Protocol platform allows users to manage and view their dedicated deployed models. These models remain active indefinitely, significantly reducing request time by eliminating the need for repeated initialization. Users are charged based on the seconds of resource usage, providing a cost-effective solution for maintaining always-on model deployments.

### Viewing Current Deployments

Upon accessing the Deployment page, users can see a list of their currently deployed models. Each model is dedicated to the user, ensuring optimal performance and availability. The page provides details such as:

* Model Name: The identifier of the deployed model.
* Deployment Status: Indicates whether the model is active or inactive.
* Resource Usage: Displays the amount of resources consumed by the model in real-time.
* Billing Information: Shows the cost incurred based on the seconds of resource usage.

### Creating a New Deployment

To create a new deployment, navigate to the "New Deployment" section. This process involves filling out a form with the following fields:

#### Endpoint Name

* Description: A unique name for your deployment endpoint. This name will be used to access the model via API requests.

#### Hardware Type

* Options:
  * Micro: 1 CPU, 2GB RAM
  * Small: 2 CPU, 4GB RAM
  * Medium: 4 CPU, 8GB RAM
  * Large: 8 CPU, 16GB RAM
  * A10: 4 CPU, 24GB RAM

Select the appropriate hardware type based on the computational needs of your model.

#### Model Selection

Choose from a list of available models to deploy:

* meta-llama/Meta-Llama-3-8B-Instruct
* meta-llama/Meta-Llama-Guard-2-8B
* mistralai/Mistral-7B-Instruct-v0.3
* google/gemma-7b
* google/gemma-2b-it
* facebook/opt-125m
* openai-community/gpt2-large
* microsoft/phi-2
* mistralai/Mamba-Codestral-7B-v0.1
* mistralai/Mistral-7B-Instruct-v0.1
* meta-llama/Meta-Llama-3.1-8B
* allenai/OLMoE-1B-7B-0924
* stabilityai/stable-diffusion-xl-base-1.0
* lucataco/moondream2
* bark/suno
* stabilityai/sdxl-turbo
* Salesforce/blip-image-captioning-large

After selecting the desired model and hardware type, submit the form to initiate the deployment process. Your model will be set up and ready to handle requests shortly.

### Conclusion

The Cluster Protocol platform provides an efficient way to manage AI model deployments, ensuring high availability and reduced latency. By following the steps outlined above, users can easily deploy and maintain their models, optimizing performance and cost-effectiveness.
