# Contributing

Before contributing to this repository, please discuss the change you wish to make
by opening an Issue or a Slack discussion with its owner. 

## Pull Request Process

### 1. Explore

Explore existing issues, as discussed in Lesson 10.4

### 2. Fork this repository

As discussed in Lesson 10.2

### 3. Create your feature branch

Create a branch with a descriptive name.

A good branch name might be (where Issue #8 is the scenario 
you're working): 8-add-feature-abc

```sh
git checkout -b <your-branch-name>
```

### 4. Implement your changes

Feel free to ask for help; everyone is a beginner at first :smile_cat:

Your patch should follow the same conventions as the rest of the project.

### 5. Make a Pull Request

At this point, you should switch back to your master branch and make sure it's
up to date with owner Admin's master branch:

```sh
git remote add upstream <repository-git-url-here>
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```sh
git checkout <your-branch-name>
git rebase master
git push --set-upstream origin  <your-branch-name>
```

Finally, go to GitHub and make a Pull Request (Lesson 11.2).

### 8. Squash the changes after review is done

We want one commit to represent one feature fix. So, the commits need to
be squashed before getting merge to master. 
