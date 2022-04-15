|No.| Subject        | Definition   |
|:-------------:| :-------------: |:-------------:|
|1| branch        |A branch is actually a independent copy of the main branch and gives us the ability to try and develope new features, without compromising the main branch. A good aspect of it would be the possibility to have multiple branches for multilpe developers to work simutaneously.|
|2| checkout      |An action by which we can move between differebt targets including files, commits and branches, being different verisons of them.|
|3| commit        |An action by which a current version of the project's staged state will be captured. These verions will be untouched unless otherwise asked by the users.      |
|4| fast-forward  |When trying to merge two commits in a condition that the second commit will be reachable for the first one easily just by following its history line, Git will fast-forward to that point. For example when master has not changed, git will move it to the lastes branch. So no conflicts will happen here!|
|5| fetch     |A command by which contents of a remote repository (commits, files and/or refs) will be downloaded to local repository but they will not be merged (unlike pull request), the user will be able to review the contents mentioned above and decide what to do next (merge or not, ...) |
|6| head |A way of showing the current commit or the latest commit on the current branch, note: if head is pointing to a commit but not its branch, git will face a condition called "detached head". |
|7| merge    |An action by which integrates two branches together, and they will join at the end of the destination branch.|
|8| remote     |This git command acts as a connection to a remote repository, it will add a name for an URL in git config file. Then user can push or pull from it. |
|9| origin/up-stream/down-stream |* Origin points to an remote repository, its a location, the original name of the remote repository; <br />* while "main" is a local branch for the local repository, and origin/name is another local branch for tracking the "main" branch on the remote "origin".<br />* There no definite upstream or downstream repository, as when we do an action like cloning we are downstream and content is flown to us from upstream, and even when we are doing an action like pushing information, we are still downstream and pushing to upstream. This can be vice versa and hence we become the upstream.|
|10| pull      |This command fetches content of a remote repository however, unlike fetch, it will merge them with the local branch and update it.|
|11| push     |This git command is used to upload the contents and commits of the local repository to a remote repository. It is the opposite of the fetch command.|
|12| repository |It is a virtual space to store our projects -and different versions of it- offered by many platforms like GitHub being among the most popular.|
|13| stash      |This command saves us from unmeaningfull commits or reseting, it stashes our work (saves it in another location) temporarily and this allows us to work on other features and give us the freedom to come back to them whenever ready for commiting.
Here is a 
[picture](https://cms-assets.tutsplus.com/cdn-cgi/image/width=600/uploads/users/585/posts/22988/image/git-stash-stashing-changes.png "picturing stash (a little fun: you just discovered an Easter Egg by hovering over this link, your prize? go out for a drink, it's on me, and if you come visit me, there shall be another round!)")
for your visual reference|

    
    
   
    
    
    
    
    
    
    
    
    
    
