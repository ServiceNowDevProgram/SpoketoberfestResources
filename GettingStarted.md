For maintainers:
 Each of the Spokes needs 1 maintainer. If you wish to be the Repo owner - please reach out to Andrew Barnes or Dave Slusher for access and include your github account name. 
 If you wish to maintain a repo you have a couple of options. Everyone can work in the same instance, you can have users fork and perform full PR, or if you have lots of contributors use GitHubCompanion.

#Same Instance: Proceed
#Small number of contributors: 
Accept the PR in GitHub - then sync the instance you are managing from to the updated Repo. You may need to stash changes, and reapply after sync. **Note: this does empty our your application locally - data in tables will be lost**

#GitHubCompanion
Download and install update set batch
Auth to GitHub via Respositories module
Setup Repo's via Repo Config module
	Important note, you need to have pulled the application from source control into the instance first
Click the *Subscribe to pull requests* UI Action
Once you have pull requests, you can open them, and use the *Open in Portal* UI action to via the differences and accept the PR. 
Once you click accept, it loads those files into the SN Instance and you must then use Studio to Commit to your Repo.

For Contributors:
Select the project you wish to join! 
Please search issue tracker before creating a new issue (problem or an improvement request). Feel Free to add issues related to the project.

If you feel that you can fix or implement it yourself, please read a few paragraphs below to learn how to submit your changes.

Submitting Changes
Comment on the issue so others know you are working on the issue.
Fork the project
Install your fork on your Personal Developer Instance (PDI) with credientials (so you have write access)
Create Branch something-descriptive
Install necessary plugins for the test (e.g. CSM tests would require CSM to be installed)
Ensure you are in the ATF scope
Create the test for this issue
Associate the test to the logical test suite
Test your test in your PDI
Commit your changes
Create a Pull Request







