# Mini_Project_Git_Version_Control_Basics 

## Hands On: Version Control System and Why it is Needed 
A version control system (VCS), also known as source control or revision control, is a tool that tracks changes to files over time, primarily used in software development to manage source code. It allows teams to collaborate effectively, revert to previous versions, and manage different iterations of a project. 

## Benefits 

- **Improved collaboration:** Facilitates teamwork and efficient code integration. 
- **Reduced risk of errors:** Allows for easy rollback to previous versions, minimizing the impact of mistakes. 
- **Increased productivity:** Streamlines development workflows and enables faster iterations. 
- **Enhanced code quality:** By tracking changes and enabling code reviews, VCS helps maintain a high standard of code. 

## Key aspects of Version Control Systems 

- **Tracking Changes:** 
VCS records every modification made to files, including additions, deletions, and modifications. 

- **Reverting to Previous Versions:**
A core function is the ability to easily revert to earlier states of the project, which is crucial for fixing errors or exploring different development paths. 

- **Collaboration:**
VCS facilitates teamwork by allowing multiple developers to work on the same project simultaneously, with the system managing the integration of their changes. 

- **History Management:**
VCS maintains a complete history of the project, including who made changes, when, and why. 

- **Branching and Merging:**
Many VCS systems allow for branching, creating separate lines of development, which can then be merged back together when ready. 

## Types of Version Control System 

Common types include centralized (like Subversion) and distributed (like Git), each with its own advantages and disadvantages. 
While primarily used for software development, VCS can be used to manage any type of file, including documents, images, and other project-related artifacts. 

## Introducing Git: A Leading Version Control System
Git is a free and open-source distributed version control system. It's widely used in software development to track changes to files, especially source code, and allows multiple developers to collaborate on the same project efficiently. Git enables tracking changes, branching and merging, and provides a complete history of a project. 

## Conceptualising Git Set Up with Tom and Jerry 

1. Initial SetUp: 

- Both Tom Jerry have Git installed on their computers.

- They clone (or download) the project repository from a central reposotory (like [GitHub](https://github.com/home), [GitLab](https://gitlab.com/users/sign_in), or [Bitbucket](https://bitbucket.org/product)) to their local machines. This gives them each a complete copy of the project, including all its files and version history. 

2. Tom and Jerry Start Working: 

- Tom and Jerry pull the latest changes from the central repository to ensure they start with the most recent version of the **index.html** file. 
- They both create a new branch from the main project. A branch in Git allows developers to work on a a copy of the codebase without affecting the main line of development. Tom names his branch **update-navigation**, and Jerry names his **add-contact-info**. 

3. Making Changes: 

- On his branch, Tom update the navigation bar in **index.html**. 
- Simultaneously, Jerry works on his branch to add contact information to the footer of the same file. 
- They commit their changes to their respective branches. A commit in Git is like saving your work with a note about what you have done. 

4. Merging Changes: 
- Once they're done, Tom and Jerry push their branches to the central repository.
- Tom decides to merge his changes first. He creates a **pull request (PR)** for his branch **update-navigation**. A PR is a way to tell the team that he's done and his code is ready to be reviewed and merged into the main project. 
- After reviewing Tom's changes, the team merges his PR into the main branch, updating the **index.html** file on the main project line.
- Jerry updates his branch with the latest changes from the main project to include Tom's updates. This steps is crucial to ensure that Jerry is working with and integrating his changes into the most current version of the project.
- Jerry resolves any conflicts that arise from Tom's changes and his own. Git provides tools and commands to help resolve these conflicts.
- Jerry pushes his updated branch and creates a PR for his changes. The team reviews Jerry's additions, and once they are approved, his changes are merged into the main project.  

## Mini Project Initial SetUp 

1. Creating a webpage in index.html file for Tom and Jerry to work on. 

- Open the terminal and a working directory and create a folder for the project,

![Creating Folder](./img/01.%20Creating%20Folder.png) 

- Changing directory to the project folder after cloning the repo from GitHub. 

![Project Folder](./img/02.%20Project%20Folder.png) 

- Creating index.html file. 

![Creating index.html File](./img/03.%20Creating%20Index.html%20File.png) 

- Filing index.html using vim as a text editor. 

![Filing index.html Code](./img/04.%20Filing%20html%20code.png) 

- Writing the a simple html code for a website using the vim editor. 

![Writing index.html Code](./img/05.%20Writing%20Index.html%20code.png) 

- Quiting or exiting the editor 

![Quiting the Text Editor](./img/06.%20Quiting%20the%20text%20Editor.png) 

- Adding and Committing all the files images, index.html and updating the README.md file 

![Add, Commit and Push](./img/07.%20Adding%20and%20Committing.png) 

![Push to Origin Main](./img/08.%20Push%20to%20Origin%20Main.png)  

## Starting Tom and Jerry Collaboration 

- **Step 1:** 
Ensures git is installed in both machines, then Changing directory to the project folder and clone the central repo. 

![Tom Clonning the Central Repo](./img/09.%20Tom%20Clonning%20the%20Central%20Repo.png) 

![Jerry Clonning the Central Repo](./img/10.%20Jerry%20Clonning%20the%20Central%20Repo.png) 

- **Step 2:** 
Tom and Jerry pull the repo to get the latest changes just to be sure.
![Tom Pull](./img/11.%20Tom%20Pull.png) 

![Jerry Pull](./img/12.%20Jerry%20Pull.png) 

- **Step 3:** 
Tom and Jerry create new branch for making individual changes on the central repo. 

![Tom Branch](./img/13.%20Tom%20Branch.png) 

![](./img/14.%20Jerry%20Branch.png) 

- **Step 4:**
Tom and Jerry switching to the branch proper to carried out the update concurrently. 

![Tom Checkout](./img/15.%20Tom%20Checkout.png)

![](./img/16.%20Jerry%20Checkout.png) 

- **Step 5:** 
Tom and Jerry makes changes to index.html by updating the navigation bar and also adding contact informations. 

![Tom Update](./img/17.%20Tom%20Update.png)

![Jerry Update](./img/18.%20Jerry%20Update.png)

- **Step 6:** 
They both add and commit the change to index.html.

![Tom Add and Commit](./img/19.%20Tom%20Add%20and%20Commit.png) 

![Jerry Add and Commit](./img/20.%20Jerry%20Add%20and%20Commit.png) 

- **Step 7:**: 
Tom checkout main to switch to branch main.

![Tom Checkout](./img/21.%20Tom%20Checkout%20Main.png)

= **Step 8:**

Tom was the first push to GitHub server and pull request from there. It was check for conflict before merging. 

![Tom Push and Pull Request](./img/22.%20Tom%20and%20Pull%20Request.png) 

- **Step 9:**
Jerry updates is branch with latest main by checking out and also pull from main. 

![Jerry Checkout and Pull](./img/23%20Jerry%20Checkout%20and%20Pull.png) 

- **Step 10:** 
Since there was no conflict Jerry after pushing a pull request was carried out.

![Jerry Push and Pull Request](./img/24.%20Jerry%20Push%20and%20Pull%20Request.png)

Both sets of changes (Tom’s and Jerry’s) are merged into the main project.
index.html now contains both the updated navigation bar and the new contact info in the footer.