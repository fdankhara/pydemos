# How project is organised

## Git commands 
> Initialise git project using command ```git init```
>
> Files you don't need to keep track of can be added to the ```.gitignore``` file
>
> To add changes to the staging area, use ```git add``` to keep an eye on changes
>
> ```git commit``` creates a snapshot of the current stage of the project and adds a branch
>
> ```git status``` will list out the state of each changed file
>
> To create an 'alternate timeline' for tests use ```git branch```. This creates a branch parallel to the main one.
> To switch between branches use ```git switch```. If you have changes you want to keep, make sure to add and commit them betfore switching between branches. 
>```git checkout``` works similarly but with branch IDs.
>
> To combine two timelines use ```git merge```.
>
>  To get a list of everything that has happened in the repository including commit IDs run ``git log --oneline```
> Add configuration using ```git config --local user.email "youremail@example.com"```
> 
> 
