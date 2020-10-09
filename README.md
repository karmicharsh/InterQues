# InterQues

_**Live at -** https://acmbvp.github.io/InterQues_

## Contribution Guidelines / Steps

For making any changes (from your local system), just following the following steps

- fork this repository into your github account (create one if you don't have it yet)
- clone it to your system (`git clone https://github.com/acmbvp/InterQues.git`)
- in the terminal run `git remote add upstream https://github.com/acmbvp/InterQues.git` (this is for taking a fresh update of the code anytime in the future)
- **IMPORTANT STEP:** get the updated code, run command `git pull upstream master` in terminal
- make the changes:
  - append your question in the list in [`ds-and-algo/index.html`](https://github.com/acmbvp/InterQues/blob/master/ds-and-algo/index.html)
  - add the solution inside `ds-and-algo/answers/<question_no>.html` _(refer [`template.html`](https://github.com/acmbvp/InterQues/blob/master/ds-and-algo/answers/template.html) for the same)_
- commit and push them to your forked repository
- create a pull request (PR)
- _Voila!_ You're done.

## Installing Git

- Download [Git](https://git-scm.com/downloads) setup for your operating system and install it.
- To check whether **Git** is installed on your system, open `cmd` on **Windows** / `terminal` on **Mac**.
- Run command `git --version` and it should display the version of **Git** installed.

## Cloning the repository using VS Code

- Open [VS Code](https://code.visualstudio.com/download).
- Go to _View > Terminal_.
- To **clone** the repo to your _desktop_, change the directory to _desktop_ by running the command `cd desktop`.
- In the terminal, run `git clone https://github.com/acmbvp/InterQues.git`.
- A folder/directory should be created on your _desktop_.
- Open that folder in **VS Code**, go to _File > Open_.
- Now you're good to go!

## Support

- Create an issue for the same and we'll help you out!
