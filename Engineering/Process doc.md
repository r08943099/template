
title: Process doc
created at: Fri Oct 14 2022 07:05:46 GMT+0000 (Coordinated Universal Time)
updated at: Fri Oct 14 2022 07:10:46 GMT+0000 (Coordinated Universal Time)
---

# Process doc

## Process to develop a feature

1.  Clone the repo `git clone repo.git`
2.  Have `yarn` and `node` installed
3.  Go to the folder `cd website`
4.  Go to branch `develop`
    1.  `git checkout develop`
    2.  `git pull`
5.  Create a new branch `git checkout -b fix/website-homepage-feature`
6.  Install the project dependencies `yarn`
7.  Start your local server `yarn dev:xxx` for website or `yarn start:xxx` for app or `yarn start:xxx` for boarding (xxx usually being your name)


    git checkout develop // Go to develop branch
    git pull // Get latest develop changes
    git checkout -b fix/mybranch // Create a new branch
    git status // To know which files have changed
    git add . // Add all the changed files for upcoming commit
    git commit -m "fix(website): Fix related stuff"
    git push -u //
    // Github - Create your Pull-request
    // Get it accepted
    // Merge it yourself

          