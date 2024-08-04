---
description: >-
  In order to publish a mod on the BYDLE Marketplace, the repository of the mod
  has to be configured correctly.
---

# Creating mod repository

To release a modification for public use, you need to configure the mod so that BYDLE systems will recognize it. To do this, create a repository on [GitHub](https://github.com). You can set the license according to your needs.

{% hint style="warning" %}
Remember to set the visibility to **Public**, as BYDLE **requires all mods to be open-source** and the code to be accessible. Ensuring transparency not only meets BYDLE's standards but also fosters community collaboration and trust.
{% endhint %}

### Submitting Source Code to the Created Repository

Follow these steps to submit your source code to the repository:

#### **1. Clone the Repository**

Open your terminal (or command prompt) and navigate to the directory where you want to clone the repository.

Run the following command:

```bash
git clone <repository-url>
```

#### 2. Navigate to the Repository Directory

Change to the directory of the cloned repository:

```bash
cd <repository_name>
```

Replace `<repository-name>` with the name of your repository.

#### 3. Add your source code

* Copy your source code files into the repository directory.
* Ensure that you include all necessary files and folders.

#### 4. Stage the changes

Use the following command to stage the files for commit:

```bash
git add .
```

#### 5. Commit the changes

Commit the staged changes with a meaningful commit message:

```bash
git commit -m "Add initial source code"
```

#### 6. Push the Changes to the Repository

```bash
git push origin main
```

Ensure `main` is the correct branch you want to push to. Replace `main` with the appropriate branch name if different.

