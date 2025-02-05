# Use a dataset

## Using Datasets in Your Project

### Overview

The "Use Dataset" page on the Cluster Protocol AI platform provides guidance on how to integrate and utilize datasets within your AI or machine learning projects. This documentation will help you understand how to access and incorporate these datasets efficiently, leveraging the power of Git for version control and collaboration.

#### Key Features

* Access Instructions: Detailed steps on how to clone and use datasets in your projects.
* Git Integration: Utilize Git to manage dataset versions and collaborate with others.

### Steps to Use a Dataset

To use a dataset from the Cluster Protocol AI platform in your project, follow these steps:

#### Prerequisites

* Ensure that Git is installed on your local machine. If not, download and install it from [here](https://git-scm.com/downloads).

#### Cloning the Dataset Repository

1. Open Terminal/Command Prompt: Access your terminal (Linux/Mac) or Command Prompt (Windows).
2.  Navigate to Your Project Directory: Use the `cd` command to navigate to the directory where you want to include the dataset. For example:

    ```bash
    cd /path/to/your/project
    ```
3.  Clone the Repository: Use the `git clone` command followed by the repository URL to clone the dataset into your project directory. Replace `example-user` and `example-repo-name` with the actual username and repository name:

    ```bash
    git clone https://git.clusterprotocol.ai/example-user/example-repo-name
    ```
4.  Access the Cloned Dataset: Once the cloning process is complete, navigate into the cloned dataset directory using:

    ```bash
    cd example-repo-name
    ```
5. Incorporate the Dataset: You can now incorporate the dataset files into your project. Depending on your project's structure and requirements, you might need to adjust file paths or modify configuration files to point to the dataset location.

#### Additional Git Commands

*   Pull Updates: To ensure you have the latest version of the dataset, periodically pull updates using:

    ```bash
    git pull origin main
    ```

    Replace `main` with the appropriate branch name if different.
*   Explore Branches: If the repository contains multiple branches, you can list them using:

    ```bash
    git branch -a
    ```

    To switch to a different branch, use:

    ```bash
    git checkout branch-name
    ```

### Best Practices

* Version Control: Regularly commit changes to your own project repository to maintain a history of modifications and facilitate collaboration.
* Documentation: Keep documentation or notes on how the dataset is used within your project for future reference or team members.
* Data Management: Be mindful of dataset size and storage requirements, especially when working with large datasets, to optimize performance and resource usage.

By following these instructions and utilizing Git effectively, you can seamlessly integrate datasets from the Cluster Protocol AI platform into your projects, enhancing your research and development efforts.
