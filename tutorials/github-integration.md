---
description: >-
  This page covers the integration and synchronization of Gitbook spaces to
  their corresponding Github repositories.
---

# Github Integration

## Overview

**Every Gitbook space \(documentation project\) is to be synchronized with its corresponding Github repository** so as to ensure that the documentation is **continuosly tracked** with its codebase and can be easily edited in **little bits as the codebase changes,** as opposed to large chunks of documentation creation or editing.

## How to integrate a space to Gitbook

### Step 1:

Create a repository on GitHub for the codebase, if one doesn't already exist. But for existing codebases, two steps are required along with the creation of the repository.

**Firstly**: Create a folder called **"docs"** in the root of your project folder or repository.

**Secondly**: Create a file called **".gitbook.yaml"** as seen below also in the root of the project repository.

{% code title=".gitbook.yaml" %}
```yaml
root: ./docs/

```
{% endcode %}

**Thirdly:** Commit and push your changes to Github.

### Step 2:

On the product dashboard, click on the "Integrations" tab and select the GitHub toggle

![Options menu](../.gitbook/assets/image%20%285%29.png)

### Step 3:

Specify the type of repositories to be displayed for you to select from. Due to the nature of sensitive credentials or details which are sometimes used or contained in our codebases. **Kindly click on "List all repositories"** in order to list **both private and public repositories** accessible to your GitHub credentials.

![](../.gitbook/assets/image%20%286%29.png)

### Step 4:

Kindly enter your github credentials when prompted and select the corresponding GitHub repository \(or codebase\) for the space or documentation project and then click on "Next"

![Select a repository](../.gitbook/assets/image%20%287%29.png)

### Step 5:

Select the github branch where the documentation files would be stored.   
**Note:** This branch should the "production" branch of the codebase where the files for the current production state of the project is stored.  
  
- Click on "sync master branch only" if your production branch is master. Or  
- Click on "select branches to sync" and enter the custom name of your production branch.

![Select or enter the custom name of &quot;production&quot; branch](../.gitbook/assets/image%20%288%29.png)

### Step 6:

Once the synchronization or import of the repository is successful, you'll get a success prompt and then you can continue to edit your documentation either from the **Gitbook website editor** or even from your **code editor or IDE** of choice.

![Success prompt](../.gitbook/assets/image.png)

