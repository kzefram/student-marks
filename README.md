# Student Marks

![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)
![Wiki.js](https://img.shields.io/badge/wiki.js-%231976D2.svg?style=for-the-badge&logo=wikidotjs&logoColor=white)
![FreeCodeCamp](https://img.shields.io/badge/Freecodecamp-%23123.svg?&style=for-the-badge&logo=freecodecamp&logoColor=green)
![GeeksForGeeks](https://img.shields.io/badge/GeeksforGeeks-gray?style=for-the-badge&logo=geeksforgeeks&logoColor=35914c)
![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Intel](https://img.shields.io/badge/Intel%20Core_i7_10th-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![DellLaptop](https://img.shields.io/badge/dell%20laptop-007DB8?style=for-the-badge&logo=dell&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

## Contents

[Description](#description) | 
[Images](#images) | 
[Installation](#installation) | 
[Licensing](#licensing)
[Contributors](#contributors) | 
[Testing](#testing)

## Description

Our new platform for managing student marks will be launching soon! This is an example website for coming soon.

[Website](kzefram.github.io/student-marks/)

## Images

## Installation

### Project Installation & Contribution Guide

Welcome! We're excited to have you contribute. Please follow these instructions carefully to get your local environment set up and to ensure a smooth contribution process.

---

#### 1. Fork the Repository

First, you need to create your own copy of the main repository. This is called "forking."

* Navigate to the main project repository page on GitHub.
* Click the **Fork** button in the top-right corner of the page. This will create a copy of the repository under your own GitHub account.



---

#### 2. Clone Your Fork & Set Up SSH

Now, you'll clone your forked repository to your local machine. We use SSH for authentication, so you'll need to have an SSH key set up with your GitHub account.

##### Getting Your SSH Key

If you haven't set up an SSH key with GitHub before, follow their official guide. It's the most secure and up-to-date resource.
* **[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)**
* **[Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)**

##### Cloning the Repository

1.  On your forked repository's GitHub page, click the green **<> Code** button.
2.  Make sure the **SSH** tab is selected.
3.  Click the **copy** icon to copy the SSH URL (it should look like `git@github.com:YOUR_USERNAME/REPOSITORY_NAME.git`).
4.  Open your terminal or command prompt, navigate to the directory where you want to store the project, and run the following command:

    ```bash
    git clone git@github.com:YOUR_USERNAME/REPOSITORY_NAME.git
    ```

---

#### 3. Initialize and Configure Your Local Repository

Once cloned, you need to configure your local copy to track the original project repository. This allows you to pull in changes and keep your fork up to date.

1.  Navigate into your new project directory:
    ```bash
    cd REPOSITORY_NAME
    ```
2.  Add the original repository as a remote named `upstream`:
    ```bash
    git remote add upstream git@github.com:ORIGINAL_OWNER/REPOSITORY_NAME.git
    ```
3.  Verify that you have two remotes: `origin` (your fork) and `upstream` (the original):
    ```bash
    git remote -v
    ```
    You should see an output similar to this:
    ```
    origin    git@github.com:YOUR_USERNAME/REPOSITORY_NAME.git (fetch)
    origin    git@github.com:YOUR_USERNAME/REPOSITORY_NAME.git (push)
    upstream  git@github.com:ORIGINAL_OWNER/REPOSITORY_NAME.git (fetch)
    upstream  git@github.com:ORIGINAL_OWNER/REPOSITORY_NAME.git (push)
    ```

---

#### 4. The Contribution Workflow

All new work must be done on a feature branch based on `development`. **Never push directly to `main` or `development`.**

1.  First, ensure your `development` branch is up to date with the `upstream` repository:
    ```bash
    git fetch upstream
    git checkout development
    git merge upstream/development
    ```
2.  Create a new branch for your feature or bug fix. Use a descriptive name.
    ```bash
    git checkout -b your-feature-name
    ```
3.  Make your changes, then add and commit them:
    ```bash
    git add .
    git commit -m "feat: A clear and concise commit message"
    ```
4.  Push your new branch **only to your fork (`origin`)**:
    ```bash
    git push origin your-feature-name
    ```

---

#### 5. Submitting a Pull Request (PR)

Once you've pushed your branch, you can open a Pull Request.

1.  Go to your forked repository on GitHub. A prompt will often appear to create a PR from your recently pushed branch.
2.  Click **"Compare & pull request"**.
3.  Ensure the base repository is the **original project** and the base branch is `development`. The head repository should be your fork and the compare branch should be your `your-feature-name` branch.
4.  Add a descriptive title and a clear summary of the changes you made.
5.  In the right-hand sidebar, under **"Reviewers,"** assign either **Karen** or **Eric** to review your PR.
6.  Click **"Create pull request"**.

**A review and approval are mandatory before any code can be merged.** Please be prepared to make changes based on feedback.


## Licensing

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

## Contributors

[Karen Bourgeois](https://github.com/kzefram)

## Testing