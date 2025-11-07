# Version Control System | Git-Github

### What is Git?
Git is a version control system. It tracks changes in your code, allows you to manage your local or remote repositories, and makes it easy to collaborate within a team. [[Doc](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)]

#### How to manage your work using Git & Github
Create a repository on Github
Generate SSH key
Clone the repo locally
Use branches
Use Git flow
Track your work
Keep your local and remote repositories updated

#### Most used Git commands
- git clone <repo>
- git add .
- git commit -m "your-work-message"
- git push
- git pull


#### How to use VS Code GUI

<img width="1390" height="1084" alt="Screenshot 2025-11-07 at 8 52 36 PM" src="https://github.com/user-attachments/assets/60e4cb54-c294-4aed-83ba-776e83e7d290" />

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
### 
