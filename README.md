# Welcome to Tech Sisters Kenya Open Source Development Sessions

**Note:** _Our practical session will incvolve write some using Vanilla JavaScript and HTML, please have your mchine set up for easy following._

## Get Started

1. Make sure you have git installed in your machine and a github account setup

- [Set Git and GitHub](https://gist.github.com/cesswairimu/a2364f507f2a1a028ea7849fd23f53bc)

2. Fork the Repository
   Forking a repository is a simple process that involves creating your own copy of the repository, cloning it locally, and setting it up for contribution. Here’s a step-by-step guide for both Linux and WSL:

## **Step 1: Fork the Repository on GitHub**

1. **Log in to GitHub.**

- Open your web browser and log in to your GitHub account.

2. **Go to the Repository URL.**

- [Visit the repository:](Tech-Sisters-Kenya/tutorial-opensource).

3. **Click the "Fork" Button.**

- In the top-right corner of the repository page, click the **Fork** button. This creates a copy of the repository in your GitHub account.

## Step 2: Clone Your Fork Locally

1. ### **Copy the Fork URL.**

- Navigate to your forked repository on GitHub (e.g., https://github.com/<your-username>/tutorial-opensource).

- Click the green **Code** button and copy the SSH or HTTPS URL.

2. ### Open a Terminal on Linux or WSL.

- On Linux, open a terminal.
- On WSL, open your preferred shell (e.g., Ubuntu for WSL).

3. ### Clone the Forked Repository.

- Run the following command (replace <your-username> with your GitHub username):

```bash
git clone https://github.com/<your-username>/tutorial-opensource.git
```

4. #### **Navigate to the Cloned Directory.**

```bash
cd tutorial-opensource
```

## Step 3: Set the Original Repository as the Upstream Remote

1. #### Add the Upstream Remote.

- The upstream is the original repository you forked from. Run the following command:

```bash 
git remote add upstream https://github.com/Tech-Sisters-Kenya/tutorial-opensource.git

```
2. #### Verify the Remote Configuration.

- Check your remotes to ensure they’re set up correctly:

```bash
   git remote -v
```

- You should see something like this:
``` bash
origin https://github.com/<your-username>/tutorial-opensource.git (fetch)
origin https://github.com/<your-username>/tutorial-opensource.git (push)
upstream https://github.com/Tech-Sisters-Kenya/tutorial-opensource.git (fetch)
upstream https://github.com/Tech-Sisters-Kenya/tutorial-opensource.git (push)
```
## Step 4: Sync Your Fork with the Upstream Repository
1. **Fetch Changes from the Upstream.**

- If there are updates in the original repository, fetch them:
``` bash
git fetch upstream
```
2. **Merge Updates into Your Local Branch.** 

- Ensure you’re on the main branch:
```bash

git checkout main
```
- Merge the changes:
```bash

git merge upstream/main
```
## Step 5: Start Contributing
1. **Create a New Branch for Your Work.**

- Always create a new branch for any changes you plan to make:
```bash
git checkout -b feature-branch
```

2. **Make Your Changes.**

- Use your preferred editor to make changes to the repository.

3. **Commit Your Changes.**

``` bash
git add .
git commit -m "Describe your changes
```
4. **Push Your Branch to Your Fork.**

``` bash
Copy code
git push origin feature-branch
```
## Step 6: Submit a Pull Request
1. Open GitHub.

- Go to your forked repository on GitHub.
2. Create a Pull Request.

- Click the Compare & pull request button and fill in the details.
- Submit your pull request to the original repository for review.

## Have any Issues/Challenges?

- [Report Here](https://github.com/Tech-Sisters-Kenya/tutorial-opensource/issues/2)
