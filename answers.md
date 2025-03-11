**question 1 answer:**
github is  a popular tool that keep tracks of software code changes that is code for software developers. 
version control aids in maintaining project integrity by providing developers a version of the changes the commited and pushed to github. this enables developers to backtrack to a specific version of the software being developed by using reseting the git repository to a specific commit. Also throught the use of multiples branches for a software product enabling developers to perform changes or trial and error to a software product without worrying of loosing or  damaging the entire product.
 
 
**To setup a new repository in github:**
create a github account
once created, the first bar near the left click the +(plus) symbol to create a new repository, oncle clicked this will open up a new page in which you are required to enter the repository name, description, type of the repository whether public or private, add a readme  file or .gitignore file and the license for the repository.


**README.md file:**
the readme file provide a short description about the software product. It aids users, developers on how to setup, use and make contributions to the software. 
It includes the following:
- title of the project or Name the software.(project title)
- description: a short statement of what the software does
- Table of Contents: for easier navigation of the Readme file
- installation: steps for the software, including system requirements and dependencies
- usage: example of how to use the software product, this include code snippets, command-line instructions, or descriptions of key features.
- Contributing: Guidelines for those who want to contribute to the project. This can include information about the code of conduct, how to submit issues or pull requests, etc.
- License of the repository
- Author: names of the people who contributed to the project
- Acknowledgements: Any thanks, credits, or references to resources that helped in the development of the project.



Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

### **Public Repository vs. Private Repository on GitHub**
GitHub repositories can be classified into **public** and **private**, each with distinct features and use cases. Below is a comparison:

| Feature          | Public Repository | Private Repository |
|-----------------|------------------|------------------|
| **Visibility**  | Anyone on the internet can view, clone, and fork the repository. | Only authorized users can access it. |
| **Access Control** | Contributors need explicit permissions to push changes. However, anyone can fork and create pull requests. | Only invited collaborators have access. Forking is disabled unless the repo is part of an organization with forking enabled. |
| **Collaboration** | Encourages open-source contributions. Anyone can submit issues and pull requests. | Limited to authorized team members. Ideal for proprietary or confidential projects. |
| **Security** | Code is publicly exposed, which may be a risk if sensitive information is accidentally included. | More secure, as only authorized users can view and edit the code. |
| **Cost** | Free for unlimited repositories. | Free for individual users but may require a paid plan for teams with advanced collaboration features. |
| **License & Ownership** | Open-source projects often use permissive licenses (e.g., MIT, Apache) or restrictive ones (GPL). | The owner controls who can access and modify the repository. |
| **Discoverability** | Searchable and indexable by GitHub and search engines, making it easier for developers to find and contribute. | Not searchable or visible to the public. |

---

### **Advantages and Disadvantages**

#### **Public Repositories**
Advantages:
- Encourages collaboration and contributions from the open-source community.
- Increases visibility and recognition for developers and organizations.
- Useful for portfolio projects, allowing potential employers to review your code.
- Beneficial for educational and research purposes.

Disadvantages:
- Security risks: Code is publicly visible, which may lead to vulnerabilities if sensitive data is exposed.
- Unwanted contributions: Can attract spam issues or low-quality pull requests.
- Less control over who can fork and use the code.

#### **Private Repositories**
Advantages:
- Security & privacy: Ensures confidential or proprietary code is not publicly accessible.
- Controlled collaboration: Only invited contributors can access and modify the repository.
- No risk of public exposure of sensitive credentials or proprietary logic.

**Disadvantages:
- Limited collaboration: External developers cannot contribute unless explicitly invited.
- Not publicly visible, making it unsuitable for showcasing work or open-source contributions.
- Costs may apply for larger teams with advanced features.


detail steps in making commits
git add fileName && git commit -m "commit message"
commit enables users to view a specific saved version for the software product in github. This is beneficial as a developer can reset the repository to a specific commit using the command ``git reset hard 'commit hash'``


Process of creating branches:
```
git branch branchName
git checkout branchName
```
branches in a repository enables developers to make changes, peform trials on the software product without affecting the main software or code. Also if the product is being contributed by a team, the team individuals can create a branch, whereby they can peform their changes and update to the software. And after the different branches can be mergeed to the main branch or software.


How Pull Requests Facilitate Code Review & Collaboration
1. Code Quality Assurance:
PRs allow reviewers to inspect changes before merging, ensuring high-quality code.
Automated tests (CI/CD) can be triggered on PR creation to detect issues early.

2. Collaboration Among Team Members:
Developers can discuss changes via comments directly within the PR.
Suggested changes can be made inline, improving readability and communication.

3. Version Control & History Tracking:
PRs maintain a clear history of code changes and discussions, which helps in debugging and auditing.

4. Approval Workflows & Permissions:
Organizations can enforce review policies (e.g., requiring multiple approvals before merging).
Teams can use labels, assignees, and project boards to manage PRs efficiently.

```
git checkout -b feature-branch
git add .
git commit -m "Added new feature"
git checkout main
git merge feature-branc
```


Forked Repository Characteristics:
- Forking a repository on GitHub is the process of creating a personal copy of someone else’s repository under your GitHub account. It allows developers to freely experiment with changes without affecting the original repository.
- forked repository exist on  GitHub (remote)
- in forked repository no, changes remain separate unless a Pull Request (PR) is merged.
- use cases of folked repository is contributing to open-source projects, modifying code independently.
- requires no permission for public repositories


Cloning Repository Characteristics:
- Creates a local copy of a repository on your computer.
- Exists on your local machine.
- does not affect the original repository, but changes can be pushed if you have write access.
- used cases of clone repository is working on a repository locally for development.
- no permission is required to clone a public repository

