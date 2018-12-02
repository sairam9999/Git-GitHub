# Git-GitHub
Basic Idea of Git:

![basiideaofgit](https://user-images.githubusercontent.com/34846166/49345044-863f2500-f64d-11e8-885e-6ff259fe1a6e.JPG)
Git works on 3-tier architecture principle where we have different stages like Local Files, Staging Area and a Repository. This 3-tier architecture is the most advantage of the Git and we won’t find this type of architecture in any version controls.
	Local files is the place where we initialize the Git and keep all the files. In Staging Area we can keep all the files changed. From Staging area we push the files to Repository. From Repository we can push the code wherever we want. Staging area is very important. In this we can find the difference of the files (what is there/ added/ removed…). We can keep track of every file. Internally every files goes to Repository from local files through Staging Area only.

Git Architecture:

![gitarchitecture](https://user-images.githubusercontent.com/34846166/49345049-89d2ac00-f64d-11e8-8d59-8f30980904e7.JPG)


Understanding the GitHub Work Flow: 
Step 1: Create a Branch
![createabranch](https://user-images.githubusercontent.com/34846166/49341469-bbcb1a80-f61b-11e8-8594-8dec20dfe17b.PNG)
	Branching is one of the core concept in Git and the entire GitHub flow is based on this. It is recommended that, every developer needs to create a branch for the Project that he is working on. We have a bunch of different ideas that are running in our mind, some of them are ready to go and some needs a rigorous testing before finalizing those features. So, whenever we create a branch, the changes that you made in the Source Code doesn’t affect to the Master Branch. So, we can experiment ‘n’ number of things on the newly created branch because branch code will not be merged to master until it’s reviewed by someone you are collaborating with in your team. Always the master branch is a deployable. Because of this, it is recommended to create a branch while working on a new feature/ fix. 

Step 2: Add Commits
![addcommits](https://user-images.githubusercontent.com/34846166/49341470-bff73800-f61b-11e8-8617-3e0b0c3cdf50.PNG)
	In Step 1, we discussed about the need of creating a branch in Git.
	After successful creation of the branch it’s time to make changes (add/ delete) on the branch which you are working on. At this stage we can add new features/ delete features/ resolve the issues which we have found.  Once you made the changes it is necessary to commit these changes. 
	Every commit has a short message which creates an idea for the other developers what this piece of code change is for and has a unique log that’s getting created. This log helps you to roll back the changes in the feature or if we want are looking for a different direction from this fix, even we can do that. Commit messages are more important because Git tracks the changes and displays in the form of commit message as a hint when you push them into the master branch. 

Step 3: Open a Pull Request
![openapullrequest](https://user-images.githubusercontent.com/34846166/49341471-ce455400-f61b-11e8-9baf-00587dbead4a.PNG)
	Pull Requests let you tell your team members about changes you’ve pushed to a GitHub repository. Once the members in the team accept your request, it’s time to discuss on the changes that needs to be merged. We can open a Pull Requests at any point during the development process: when you’ve a basic prototype ready/ initial idea of the feature and you can also open this Pull Request without writing a single line of the code also.

Step 4: Discuss and Review your Code
![discussandreviewyourcode](https://user-images.githubusercontent.com/34846166/49341473-d8675280-f61b-11e8-8fc5-71f71fa3782f.PNG)
	Once the Pull Request (Step 3) was opened, the team members will review your code changes and can come up with the questions/ comments/ feature changes on which you are working. We can also start pushing the code to the branch in order to get some feedback/ comments/ guidance of the features on your commits. If someone in the team comes up with the comments, we can make the code changes and commit those changes to the branch. Git can keep track of those comments and commits which we’ve done.

Step 5: Deploy
![deploy](https://user-images.githubusercontent.com/34846166/49341477-ddc49d00-f61b-11e8-80a6-f1afe8669a81.PNG)
	This is the Step where we can deploy from a branch for final testing in production before merging to master. Once the Pull Request, Discuss Proposed changes and tests are passed we can release to the production. If we find any issues in production, we can still make changes in this branch before merging into master for production.

Step 6: Merge
![merge](https://user-images.githubusercontent.com/34846166/49341481-e74e0500-f61b-11e8-9a07-b4e7934ac58e.PNG)
	Once the changes are verified in production, it’s time to push those changes to your master. Once you are done with pushing the changes, Pull Requests preserve a record of the archived changes of our code. These changes will help others in the team how the decision was made before making the changes. 
	Even we can close the Test Track items (bugs) from the previous versions of software release by merging the Pull Requests. For example: Closed Test Track Item #55. 

