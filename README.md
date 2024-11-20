Welcome to Tech Sisters Kenya Open Source Development Sessions

**Note:** *Our practical session will incvolve write some using Vanilla  JavaScript and HTML, please have your mchine set up for easy following.*

# Get Started
Make sure you have git installed in your machine and a github account setup – 
- [Set Git and GitHub](https://gist.github.com/cesswairimu/a2364f507f2a1a028ea7849fd23f53bc)

## Have any Issues/Challenges?
- [Report Here](https://github.com/Tech-Sisters-Kenya/tutorial-opensource/issues/2)


Welcome to Tech Sisters Kenya Open Source Development Sessions! These webinars are designed for anyone interested in contributing to open source projects, whether you're a beginner or a seasoned developer.

---

## 🗓️ Upcoming Webinar Details
**Session Dates**: All Wednesdays of November
**Time** 8:00pm -10:00pm 
**Topic**: Open Source Development
**RSVP to Join Webinar** :[RSVP Here](https://forms.gle/pLiqGB3gjqr9WRCu7)

### 🎯 How to Prepare:
1. Make sure you have **Git installed** on your machine and a **GitHub account** set up. Follow this [setup guide](https://gist.github.com/cesswairimu/a2364f507f2a1a028ea7849fd23f53bc).
2. Install a code editor like [VS Code](https://code.visualstudio.com/).
3. Ensure your machine is set up to work with **JavaScript (JS)** and **HTML**.

If you encounter any issues during setup, raise your questions here: [GitHub Issues](https://github.com/Tech-Sisters-Kenya/tutorial-opensource/issues/2).  
*Tip: Include a screenshot for faster assistance.*

---

## 📂 Resources

### **Presentation Slides**
- [Session 1: Getting Started with Open Source Development](https://docs.google.com/presentation/d/1iav6EteJMdrTJ9E89ox4-gli5yjvHqdsDi2Bid5Sz4M/edit#slide=id.g31288d19589_0_50)
- [Session 2: Figma Mockup Design for a Website](https://docs.google.com/presentation/d/1ENtBX3fgv2MMN42gWGmaZl6PVJY6EAVuoqEG8rFCW8A/edit#slide=id.g314bed126c0_0_0)

### **Recordings**
- [Session 3: Part 1](https://app.bluedothq.com/preview/673e191f3fe4c623d7d358ac)  
- [Session 3: Part 2](https://app.bluedothq.com/preview/673e2a1c3fe4c623d7d53924)

### **Figma Mockup**
- [Simple To-Do App Design](https://www.figma.com/design/vWe4dnZVUnP0sVrWY5sJ7H/Simple-To-Do-App?node-id=3-3&t=RkqG6IPrrWJAcqzs-1)

---

## ✨ What to Expect
- Hands-on coding sessions with basic **JS/HTML**.
- Insights into how to discover and contribute to open source projects.
- Resources and guidance to kickstart your journey.

---

## 🤝 How to Contribute
1. Fork the To-Do-App repository: [todo-app](https://github.com/Tech-Sisters-Kenya/todo_sample_app) 
2. Create a new branch for your changes: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature name"`.
4. Push your branch: `git push origin feature-name`.
5. Open a pull request for review.

---

## 💬 Community Support
Join the discussion or raise any questions on [GitHub Issues](https://github.com/Tech-Sisters-Kenya/tutorial-opensource/issues).  
We’re here to help!

---

## 📧 Contact
For any inquiries, feel free to reach out or connect with us during the webinar or email us @techsisterskenya@gmail.com!

--

Happy coding! 🚀

## 🚀 Join the Tech Sisters Kenya Community! 💻✨

Are you passionate about technology, growth, and networking with like-minded individuals?  
Tech Sisters Kenya is the perfect place for you! 🌟

🎉 **What We Offer:**
- 🤝 Supportive community of women in tech
- 💡 Mentorship and learning opportunities
- 📅 Events, workshops, and networking sessions
- 🌍 A safe space to share, learn, and grow together

📲 **Join us today and become part of a thriving tech community!**  
👉 [Click here to connect with us on Linktree!](https://linktr.ee/techsisterskenya)

Let's build the future together, one tech sister at a time. 💪  
#HeyTechSister 💜

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
