# Onchain-Squad-Team

Welcome to the Onchain Squad Team. This repository should help you to understand how to collaborate on open-source projects you like to work on but might have fear of screwing up something. At least I had the issue.

1. Your first step is to create an issue. Usually, if you use open-source, you might not know how to fix a specific bug but someone else might have the knowledge. Or you just want to start a simple discussion on an idea you might have in mind.

   - On this repository, the issue is to write something like this:

   ```markdown
   I want to be a part of the Onchain Squad Team but my name is missing in the README.md file. Please add me.
   ```

2. After you have sent your issue, you go through the debugging and collaboration phase.

   1. Fork this repository to your own GitHub account so you have your own copy to make changes to.
   2. In your Forked reposetory, go to the green Code button and copy the URL (using SSH).
   3. In your terminal, create a new folder: `mkdir myCollaboration`.
   4. Go into the folder: `cd myCollaboration`.
   5. Clone the repository: `git clone <url>`.
   6. Open the project on your IDE or Terminal.
   7. Make sure you have the most up-to-date code. In your terminal, write:
      ```bash
      git pull
      git fetch
      ```
      Even if Git doesn't show new code, this is a good practice to follow.
   8. Create a new branch. The branch should include your GitHub account name and the project you are working on, like so:
      ```bash
      git checkout -b myGithubAccount-addANewName-issueID
      ```
      On open-source projects, collaborators can track the bug and your solution easier with this approach.
   9. After you have created a new branch, update the file. In this example, add your name to the README.md file and push the solution to your repository.
   10. Now it's time to shine and make your first Pull Request to the original repository. If your code is correct, you can update your issue and mark the issue with your Pull Request ID as resolved.

Congratulations! You are now a team member of Onchain Squad. Scroll down to your user account entry and make sure the README.md is updated.

| Github Name | Discord ID        | Telegram          | Twitter                                                 |
| ----------- | ----------------- | ----------------- | ------------------------------------------------------- |
| John Doe    | @johndoe#1234     | @johndoe_telegram | [@johndoe_twitter](https://twitter.com/johndoe_twitter) |
| Pate87      | @paddy87          |                   | [@DevPate9](https://twitter.com/DevPate9)               |
| Your Name   | @yourdiscord#0000 | @yourtelegram     | [@yourtwitter](https://twitter.com/yourtwitter)         |
