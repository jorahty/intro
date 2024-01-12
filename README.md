# Intro to Git, Github and Docker

Hi 👋!

Let's practice the CSE 113 homework workflow!

## Background Reading

If you're not already comfortable with GitHub and Docker:

1. [Getting Started with GitHub](https://github.com/ucsc-cse113-winter24/github-starter-course/blob/main/README-github.md).
2. [Getting Started with Docker](https://github.com/ucsc-cse113-winter24/github-starter-course/blob/main/README-docker.md).

## Your task

Write a Python program `git-101.py` that reads two integers from standard input (stdin) and prints out their sum to standard output (stdout).

The code must be in a file named `git-101.py` for the autograder to run correctly.

**⚠️ Important**: Do not modify the `.github` directory.

## Docker Image

Make sure you have pulled the Docker image `reeselevine/cse113:latest` to your local machine.

This image is the same image used by the autograder!

You can use this image to create a container (on your local machine) that is identical to the container the autograder will use.

You only have to pull this image once. We will use this image for the entire quarter.

## Workflow

1. Clone this repository to your local machine
2. Write your program in a file named `git-101.py`
3. To test your program inside a container identical to the one used by the autograder, start a new container using the `reeselevine/cse113:latest` image and mount the local repository folder to the container. (_Hint: the `-v` option_)
4. Test your solution inside the container. For this homework, test your code using the command `python git-101.py < test-case.in`
6. Commit your changes
7. After you commit, **if it is the first time you are submitting** the homework, create a `submit` branch using the command `git checkout -b submit`
8. Within the new branch, you can push to Github with `git push origin submit`
9. On Github, check the autograder results by clicking the **Actions** tab:

![](https://docs.github.com/assets/cb-15465/mw-1440/images/help/repository/actions-tab-global-nav-update.webp)

In case of questions, please share it through Piazza!
