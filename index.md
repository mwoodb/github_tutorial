
# Step 1: Create an account

1. [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

2. [Create an account](https://github.com/join)

3. Join the lab organization(s)


# Step 2: Create a repository

A repository is essentially a folder to hold all the files for a project and track changes.

1. Choose a name and write a description.

2. Link it to a local folder on your computer.

> `$ echo "Example of an experiment repo" >> README.md`
>
> `$ git init`
>
> `$ git add README.md`
>
> `$ git commit -m "first commit"`
>
> `$ git branch -M main`
>
> `$ git remote add origin https://github.com/mwoodb/github_tutorial.git`
>
> `$ git push -u origin main`


4. Edit your task code and push changes.


# Step 3: Work with collaborators

1. Invite collaborators to repository.

2. Create a branch for yourself.

> A branch is where you can work on a copy of the code that might not be ready to be in the main version. 

![](https://guides.github.com/activities/hello-world/branching.png)

To make a new branch:

> `$ git checkout -b <new-branch>`

Or to move to an existing one:

> `$ git fetch --all`
> `$ git checkout <branch-name>`


3. Open a pull request.

> To propose your changes and incorporate them into a different branch (e.g. main), you can make a *pull request*. After the request is made you or a collaborator can review the changes and *merge* them into the other branch.


# Step 4: Create a project

A project is a way to track issues or milestones.

![](https://github.com/mwoodb/github_tutorial/blob/main/github-project-screenshot.png)

1. Name the project and choose a template

> This will create a board that organizes issues and tasks. 
>
> For example, you can have columns like *To Do* and *In progess* that track whether specific issues have been resolved.
> This can be automated so that when you close an issue it is automatically transferred from *To Do* to *Done*.

2. Create new issues.

> Issues can be anything from bugs to new features that need to be added. These can be assigned to specific projects, milestones, and people.

3. Create milestones.

> Milestones are another way to track progress on a project. For example, when developing a task there could be separate milestones for different versions or different stages of data collection.


# Step 5: Publish as a website


# Step 6: Saving data to a separate repo on Github
