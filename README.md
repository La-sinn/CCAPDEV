# sum project name

This is a project desc

## Folder Structure

```text
CCAPDEV/
├── README.md
├── index.html
├── DELETE_ON_SUBMISSION/
├── styles/
├── pages/
├── assets/
|   ├── fonts
|   └── images
└── model/
```
### Delete on Submission/
Contains a bunch of pdf files we're going to need throughout the project for reference

### styles/
Contains CSS code for the website

### pages/
Would usually contain JavaScript code pero idk how that works pa

### assets/
Contains fonts and images necessary for the webpages

### model/
Contains the MongoDB files and other backend resources necessary for the project

## How to properly use da repo

Ensure that you have first done and resolved any authentication requests
```cmd
git clone https://github.com/La-sinn/CCAPDEV
```
You should see a folder named CCAPDEV now

Main is reserved for stable, developed outputs, and (hopefully) bug-free. Developing new features requires branching to ensure that the main is unaffected.
- ### Branching
Branching is a way to go crazy with your code while leaving main unaffected, NOT MAKING A NEW MAIN. Before you branch out, it is good practice to;  

- #### Check if main is up to date
```cmd
git switch main
git status
git pull
```

Then you can branch out safely using
```cmd
git switch -c <New Branch>
git switch <branch name>
```

Common git calls with help
```cmd
git help <feature>
git help add
git help commit
git help push
git help pull
git help fetch
```

- ### Committing Changes
This step ensures that you are staging the files and are ready to add them to the repo
```cmd
git add example.c
git add -A 
```

Then, after you've added the staged files, you do
```cmd
git commit -m "Your message here"
```

At this point, you're eager to push into the main branch. Two things can happen;
```cmd
git push
```

- #### Merge Conflict
As much as possible, we try to avoid this, but it's not completely avoidable in a collaborative work setting. Merge conflicts happen because two people worked on the same line of code and have different changes. Resolve this in VSC by either accepting both changes (same line of code but different features), accepting incoming changes (their code is correct), or accepting outgoing changes (your code is correct).
- #### No issues
Well done, that's version control :)

