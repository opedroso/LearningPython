# LearningPython

## Setup

### Use VSCode

If you are not using VSCode, you can download it from here:

https://code.visualstudio.com/Download

VSCode is Microsoft's Open Source IDE that is minimalist and can be tailored for every language you need by loading extensions

### VSCode extensions

For best results using this project, use VSCode and load the following VSCode extensions:

- GitHub Pull Requests (0.8.0)  # helps manage Pull Requests (PR)
- Python (2019.6.22090)         # brings the modules to execute/debug Python code
- Markdown PDF (1.2.0)          # general app that allows to view side by side markdown files as well as generate PDFs

## Starting up

Start by forking the original project (eduardokuhn/LearningPython) to your GitHub user, which will create your-github-username/LearningPython project. You can do this by visiting https://github.com/your-github-username/LearningPython and clicking on Clone (select HTTPS option), then select to copy this project's URL to your clipboard.

Then clone your forked project to your computer, by getting a CMD window and typing something like this (the project URL is pasted from the clipboard):

```bash
# This will create the directory LearningPython on your current directory.
git clone https://github.com/your-github-username/LearningPython.git
```

Then open the cloned project in VSCode:

```bash
# change your directory to this directory:
cd LearningPython
# start vscode here
vscode .
```

## Day to Day tasks

Now if you select a file on the left and make modifications, these are made to your local disk copy.

Once you are happy with them, you can save the file and then right-click the file and select Commit to make these changes permanent to your local copy of the project (still locally).

To save these changes to GitHub, you will then execute a Pull in VSCode or Git, which will make the GitHub your-github-username/LearningPython project even with your disk copy.
Your forked project will now be one change off from the original project you forked from.

If you believe you made changes that the original project owner would like to add, you can now make a Pull Request.
Visit your-github-username/LearningPython and select "New Pull Request".
This will create combine all your changes made since you forked the project and add a Pull Request to the original project.
The owner of that project will then code review your changes and merge your changes (or not) to the main project.
S/he may also add comments to your Pull Request that you should follow if you want have your PR merged.

In a nutshell, that is how open source projects are contributed to in GitHub.

