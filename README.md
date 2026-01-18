project:
  name: git-practice
  description: >
    A hands-on Git and GitHub practice repository demonstrating
    real-world version control workflow including commits,
    branching, merging, and rollback.
  purpose: Internship / learning assignment

tools:
  primary:
    - Git
    - GitHub
  alternatives:
    - GitLab
    - Bitbucket

setup:
  requirements:
    - Git installed on local system
    - GitHub account
  configuration:
    username: configured globally using git config
    email: configured globally using git config

workflow:
  steps:
    - Initialize local Git repository
    - Create and track files using git status, add, commit
    - Link local repository with remote GitHub repository
    - Push commits to GitHub
    - Create a feature branch
    - Make changes and commit them
    - Merge feature branch into main
    - Practice rollback using git log, checkout, and reset

branches:
  main:
    description: Stable production-ready branch
  feature-test:
    description: Experimental branch for practicing changes

rollback:
  methods:
    - git checkout <commit-hash>
    - git reset --hard <commit-hash>
  note: >
    Reset is destructive and should be used carefully.

deliverables:
  - GitHub repository link
  - Commit history screenshots

final_outcome:
  learning:
    - Understands difference between local and remote repositories
    - Can manage commits and branches
    - Can safely revert or reset changes
  level: Intern-ready Git workflow understanding
