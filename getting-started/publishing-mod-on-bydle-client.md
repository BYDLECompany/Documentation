---
description: >-
  In order to publish a mod on the BYDLE Marketplace, the repository of the mod
  has to be configured correctly.
---

# Publishing mod on BYDLE Client

To release a modification for public use, you need to configure the mod so that BYDLE systems will recognize it. To do this, create a repository on [GitHub](https://github.com). You can set the license according to your needs.

{% hint style="warning" %}
Remember to set the visibility to **Public**, as BYDLE **requires all mods to be open-source** and the code to be accessible. Ensuring transparency not only meets BYDLE's standards but also fosters community collaboration and trust.
{% endhint %}

<figure><img src="../.gitbook/assets/image.png" alt="" width="375"><figcaption><p>Creating new repository on <a href="https://github.com">GitHub</a></p></figcaption></figure>

## Submitting Source Code to the Created Repository

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

{% hint style="info" %}
You can also use other tools, such as [GitHub Desktop](https://github.com/apps/desktop), to submit your source code to the repository.
{% endhint %}

## Creating first release

To create your first release, start by tagging the repository with a version identifier. The tag should be in the format `DunHero-X.Y.Z`, where `X.Y.Z` represents the version number of DunHero. Next, prepare a ZIP archive containing your mod files. Ensure that the highest-level directory in the ZIP file includes the mod’s `dll` file directly. **If you're mod is compatible with all DunHero versions, just don't tag the release.**

Once you have created the appropriate tag, you should prepare your mod for release. This involves creating a ZIP archive of your mod files. Ensure that the structure of the ZIP file is correct: the highest-level directory within the ZIP should contain the mod’s `dll` file directly. This structure is crucial as it ensures that users can easily access and install the mod without navigating through multiple subdirectories.

After preparing the ZIP file, navigate to the "Releases" section of your repository on the hosting platform. Here, you will draft a new release by selecting the option to "Draft a new release." Enter the tag you created earlier, such as `DunHero-0.2.1`, and provide a meaningful title for the release. You can also include additional details in the description field to give users context about what this release includes.

Next, upload the prepared ZIP file to the release. This ZIP file should contain your mod and adhere to the specified directory structure. Once the file is uploaded, review the release details to ensure everything is correct. Finally, publish the release.

## Publising mod on BYDLE Client

To submit your mod to the BYDLE client, you must use **Google Form** to complete the submission process. Navigate to the provided Google Form link and ensure you fill out all the required fields with accurate information about your mod. This includes details such as the mod name, description, icons and any other relevant specifications. Providing complete and accurate information in the form is essential for a successful submission and proper integration of your mod into the BYDLE client.
