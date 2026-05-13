<h1 align="center">
  <br>
  SE Lab
  <br>
  <small>Assignment 1: Static Website</small>
</h1>

<p align="center">
  <b>Group 5</b>
  <br>
  Pouria Mahmoudkhan (401110289)
  <br>
  Yasna Noushiravani (401106674)
</p>

---
<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#branches">Branches</a> •
  <a href="#conflicts">Conflicts</a> •
  <a href="#main-branch-protection">Main Branch Protection</a> •
  <a href="#github-pages-deployment">Github Pages Deployment</a> •
  <a href="#kanban-board-and-project-progress">Kanban Board and Project Progress</a>
</p>

## Overview
In this assignment we practiced essential skills needed to develop a project, including
1. Basic github commands
1. Merging branches
1. Resolving conflicts
1. Creating pull requests and reviewing them
1. Using github actions to automate Github Page deployment
1. Protecting a branch by only allowing changes via pull requests
1. Creating projects and kanban boards to record and manage progress

## Branches
This repository has 8 branches.
### Feature branches
1. Index: This branch is related to the developement of the main page and was created quite early in the process. As the commits suggest, the files added to the project at this stage were
    - index.html: the HTML file for the landing page
    - style.html: the CSS file containing all of the styling used in the project
    - images: the folder containing the pictures used in the website

    ![index branch commits](report/index-commits.png)
    After completing the developement of the main page, we merged this branch back into main using pull requests.
    ![merging index into main](report/merge-index-main.png)

1. Review: In this branch we built the review tab. The changed files are
    - review.html: the HTML file for the review page, containing navbars and some reviews
    - style.css: this file was modified to contain the styles used by the review page

    ![review branch commits](report/review-commits.png)
    This branch was developed in parallel with the roger branch.

1. Roger: 


## Conflicts

1. The first conflict occured while merging the index branch. The class field in the navbar wa not present in one side of the conflict and the order of the links were different. The conflict was resolved in favor of the commit where the class field was present.
![index merge conflict](report/merge-index-conflict.png)
as can be seen in the picture above.

2. The second conflict occured while merging the roger branch. We both had changed the css file in parallel. The conflict was resolved by accepting both changes. This resolution was done in github.
![roger merge conflict](report/merge-roger-conflict.png)
as can be seen in the picture above.

## Main Branch Protection

For this requirement we have set the rule to require a pull request before merging along with at least 1 approval from an admin.
![require pull](report/require-pull.png)

The review of the pull request can be seen in the picture below. This was during the index merge with main.

![pull merge](report/pull-request-index-main.png)


## Github Pages Deployment

Github pages was also created and deployed in github actions in the following url:
https://pmksh.github.io/selab-1/

![pages](report/pages.png)
Made using the static html option, it was merged into main after review.
![pages](report/static-yml.png)

## Kanban Board and Project Progress