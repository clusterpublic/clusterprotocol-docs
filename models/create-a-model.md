# Create a model

## Creating an AI Model Repository on Cluster Protocol

Welcome to the documentation for creating an AI model repository on the Cluster Protocol platform. This page will guide you through the process of setting up a new AI model repository, which is essentially a Git repository hosted on the platform.

### Accessing the New Model Page

To create a new AI model repository, navigate to the following URL: [https://beta.clusterprotocol.ai/models/new](https://beta.clusterprotocol.ai/models/new)

### Form Fields for Creating a New Model

When you access the page, you will encounter a form designed to capture essential details about your new AI model repository. Below are the fields you need to fill out:

* Name: Enter a unique name for your AI model repository. This name will be used to identify your repository within the Cluster Protocol platform.
* Visibility: Choose the visibility level for your repository. You can select between public and private options depending on whether you want your repository to be accessible to others or restricted.

Once you have filled out all the necessary fields, submit the form to create your AI model repository.

### Pushing Committed Code to Your Model Repository

After creating your AI model repository, you can push your committed code to it using Git. Follow these steps to push your code to the repository located at `https://git.clusterprotocol.ai/example/repo-name`.

#### Step 1: Initialize Your Local Repository

If you haven't already initialized your local directory as a Git repository, do so by running:

```bash
git init
```

#### Step 2: Add Your Remote Repository

Add the remote repository URL to your local Git configuration:

```bash
git remote add origin https://git.clusterprotocol.ai/example/repo-name
```

#### Step 3: Stage and Commit Your Changes

Stage the files you want to commit:

```bash
git add .
```

Then, commit the changes with a meaningful message:

```bash
git commit -m "Initial commit"
```

#### Step 4: Push Your Changes

Finally, push your committed changes to the remote repository:

```bash
git push -u origin main
```

Ensure that you replace `main` with the appropriate branch name if your repository uses a different default branch.

### Conclusion

By following these steps, you can successfully create and manage an AI model repository on the Cluster Protocol platform. For further assistance or more advanced configurations, refer to the platform's comprehensive documentation or contact support.
