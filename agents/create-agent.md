# Create Agent

## Creating a New AI Agent in Cluster Protocol Spaces

Creating an AI agent in Cluster Protocol Spaces is a straightforward process that allows you to set up a new project with customizable settings and resources. This guide will walk you through the steps of creating a new agent using the provided form, selecting from various templates and hardware tiers, and pushing your code to the associated repository.

### Creating a New Agent

To create a new AI agent, navigate to the "New Space" page. Here, you'll find a form designed to gather essential information and preferences for your new agent. The form includes the following fields:

#### 1. Name

Enter a unique name for your AI agent. This name will be used to identify your project within the Cluster Protocol platform.

#### 2. Visibility

Choose the visibility setting for your agent. Options typically include:

* Public: Anyone can view and access the agent.
* Private: Only authorized users can access the agent.

#### 3. Template

Select a template that best suits your project's needs. Available templates include:

* Docker: For containerized applications.
* Gradio: Ideal for building interactive machine learning demos.
* Streamlit: Perfect for creating data apps quickly.
* Static: For static websites or applications.

When you select a template, prebuilt code specific to that template is automatically pushed to your repository. This code provides a starting point, allowing you to focus on customizing and developing your agent further.

#### 4. GPU Tiers

Choose a hardware tier that matches your computational requirements. The available options are:

* CPU Basic: 2 vCPU - 8GB
* CPU Medium: 4 vCPU - 16GB
* A10 GPU Basic: 2 vCPU - 16GB
* A10 GPU Medium: 4 vCPU - 32GB

These tiers determine the computational power and memory allocated to your agent, impacting its performance and capabilities.

### Pushing Code to Your Repository

Once your agent is created, you can push your code to the associated Git repository. The repository URL follows the format: `https://git.clusterprotocol.ai/<username>/<agent-name>`. Here's how to clone, commit, and push changes to your repository using an example agent named "my-ai-agent".

#### Example: Cloning and Pushing Code

1.  Clone the Repository

    Open your terminal and run the following command to clone your repository:

    ```bash
    git clone https://git.clusterprotocol.ai/your-username/my-ai-agent.git

    ```
2.  Navigate to the Project Directory

    Change into the project directory:

    ```bash
    cd my-ai-agent

    ```
3.  Make Changes :

    Add or modify files as needed. For example, you might update the Python script provided by the template or add new data files.
4.  Commit Your Changes

    Stage your changes and commit them with a descriptive message:

    ```bash
    git add .
    git commit -m "Updated model training script"

    ```
5.  Push Changes to the Repository

    Push your committed changes to the remote repository:

    ```bash
    git push origin main

    ```

By following these steps, you can easily manage and update your AI agent's codebase.

### Conclusion

Creating a new AI agent in Cluster Protocol Spaces is a seamless process that empowers you to leverage prebuilt templates and customizable hardware tiers. With the ability to push and manage your code through a dedicated Git repository, you can efficiently develop, test, and deploy your AI solutions. Start building your next AI agent today and explore the possibilities within Cluster Protocol Spaces!
