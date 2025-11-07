# Version Control System | Git-GitHub

### What is Git?
Git is a version control system. It tracks changes in your code, allows you to manage your local or remote repositories, and makes it easy to collaborate within a team. [[Doc](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)]

#### How to manage your work using Git & GitHub
- Create a repository on GitHub
- Generate SSH key
- Clone the repo locally
- Use branches
- Use Git flow
- Track your work
- Keep your local and remote repositories updated

#### Most used Git commands
- git clone <repo>
- git add .
- git commit -m "your-work-message"
- git push
- git pull


#### How to use VS Code GUI

<img width="1390" height="1084" alt="Screenshot 2025-11-07 at 8 52 36 PM" src="https://GitHub.com/user-attachments/assets/60e4cb54-c294-4aed-83ba-776e83e7d290" />

### Teamwork | How to use branches
A branch is a separate line of development. It allows you to work on new features or fixes without affecting the main codebase. The default branch is usually main

- git checkout -b "branch-name"

- ##### Best Practice fro Naming Branches
    - add: A new feature.
    - change: Generic changes in the code base, anything that is related to maintaining or improving the code.
    - fix: A bug fix.
    - test: Adding missing tests or correcting existing tests.


    #### Feature-Based Branching
    It is a common Git workflow strategy where each new feature or improvement in your project gets its own separate branch

        main
        |
        *---* release-1.0
                \
                *---* develop
                    \
                        *---* feature-login
                        *---* feature-cart

    ##### Steps to manage your work
    - Create a new branch
    - Push your work
    - Open a PR with a clear title, description (add a screenshot or video), and labels
    - Assign a reviewer for your code
    - Review your teammate's code
    - Approve the PR
    - Merge the PR
    - Delete the branch

### Tasks Management
- Use projects
- Use issues
- Use branch rules
<img width="1146" height="711" alt="Screenshot 2025-11-08 at 12 18 06 AM" src="https://github.com/user-attachments/assets/e1f5f8a6-6571-4ed3-9097-ea2705b5f985" />

