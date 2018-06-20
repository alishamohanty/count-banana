# count-banana
Banana count
Count-Banana is a repository for testing the functionality of the an App which was assigned to me as a pre-task while applying for the exercism project by RGSoC during my application submission for 2016.

The goal of this project is to create a bot that will automatically create issues when there are updates to the problem specifications repository.
this implement a GitHub App (presumably using Probot) that:
-Listens for the PushEvent 
 event that gets triggered when you push code to a GitHub repository (see the documentation about webhooks for more information).
-Looks for the word banana in all the commit messages that are a part of that push.
