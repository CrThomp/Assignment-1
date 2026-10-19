Branching:
Documentation - this branch is build by the user (me) to keep track of resource questions
feature1 - this branch was designed to make the user familiar with resolving conflicts, making commits about these conflicts and merging the into the dev branch
feature2 - this branch was designed to help the user further understand squashing commits, archiving commits and adding commits before rebasing into the dev branch
feature3 - this feature introduces cherry-pick commits before merging the two branches
dev - this branch is the "development" branch that acts as a middle man of a working copy between the features and the final main branch
main - this is the master branch of the project directory

The differences between merge, rebase, squash and cherry-pick in the git software are as follows:
merge allows a combination between the branches creating a universal commit history
Rebase rewrites the history of the branches and creates a linear log to maintain the combination of the commits
Squash combines multiple commits into one commit to clean up the --oneline
cherry-pick allows an application of a single commit from one branch to another

Throughout the task the history and status observed in the git history was different between features1 - 3. Each one mimicked what the objective of the task was - to show the differences and changes to the --oneline and status histories to describe the pathways of actions to obtain them. feature1 was focused on merging, feature2 was focused on squashing and combining and feature3 focused on cherry-picked commits for the entire history. 
Each feature will be applied to future projects. On branches were the changes are very direct and very linear, the skills learned in feature1 to merge the branches will be utilized. In projects where there are more abstract solutions, say different versions that are tested separately before combined, something like squashing commits to come up with a universal commit history will be used. In projects with multiple users, feature3 and the skill of cherry-pick will be utilized to show the "best option" commit between the branches. Each feature branch is intended to be cleaned up before being merged into the dev branch and all changes should be committed and documented to retrace steps. Changes to the main or master branches should be limited as the intent of git is to provide a secure version history. 