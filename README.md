# How to collaborate on Github projecrt

This repository should help you to understand how to collaborate on open-source projects you like to work on but might have fear of screwing up something.
Here are the steps to get started:

Owerview of [Contributing to a Project - Git Book](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)

1. Your first step is to create an issue. Usually, if you use open-source, you might not know how to fix a specific bug but someone else might have the knowledge, or you just want to start a simple discussion on an idea you might have in mind.

   - On this repository, the issue is to write something like this:

   ```markdown
   I want to be a part of the Onchain Squad Team but my name is missing in the README.md file. Please add me.
   ```

2. After you have sent your issue, you go through the debugging and collaboration phase.

   1. Fork and clone this repository </br>

   - Follow the steps provided in the
     [Fork a repository - Github Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

   2. Make sure you have the most up-to-date code. In your terminal, write:
      ```bash
      git pull
      git fetch
      ```
      Even if Git doesn't show new code, this is a good practice to follow.
   3. Create a new branch. The branch should include your GitHub account name and the project you are working on, like so:
      ```bash
      git checkout -b myGithubAccount-addANewName-issueID
      ```
      On open-source projects, collaborators can track the bug and your solution easier with this approach.
   4. After you have created a new branch, update the file. In this example, add your name to the README.md file and push the solution to your repository.
   5. Now it's time to shine and make your first Pull Request to the original repository. If your code is correct, you can update your issue and mark the issue with your Pull Request ID as resolved.

Congratulations! Scroll down to your user account entry and make sure the README.md is updated.

| Github Name |
| ----------- |
| John Doe    |
| Pate87      |
| Your Name   |
