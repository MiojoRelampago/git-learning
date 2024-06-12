# Git-learning

Learning about git and >:D

# First Step

This is the first change i'll be doing in git commands using git add to stage the content
Afterwards i'll be using commit to change it back to unmodified
And using DIFF, i can check upon changes that have been done upon the older version of it
Or if you're using VSC like me, you can check directly upon the UI the changes that have been made in the code

# Using LOG and RESTORE

Using the command LOG, you can get some info on the previous launches that were done into this files and it's hashes
Hashes are the way that git/github can turn back to previous versions of a code that were changed

Restore whatsoever, rests on "Restoring" to the previous changes, not exactly a previous version, but if you made new changes into your branches, you can turn back with RESTORE
This can be done on modified state or staged state, if you made a -add but changed your mind midway of the process, you remove it from the staged state or modified if used again

# Using PUSH and PULL & Learning more about Remote Branches

On this change, we will be using PUSH to send this changes directly into the our github, since it's the place that we've been working on
Upon using it, the changes that couldn't be checked on the website, will be on this new version of the code
This changes will all be sent to the desired place but let's talk like we are working on a team, that made different changes on a branch, and commited them, what can you do in this case?
You can use directly the command PULL to "download" all the changes that have been done within that branch you're working on and merge with your current code

**THIS CHANGE WAS DONE WITHIN THE GITHUB AND WILL BE PULLED ON TO TEST**

But let's say that you want to pull a change from your branch that was done, but you don't want to merge it yet, you want to check the differences from your current code and from there, you might wanna merge and add to your current code
We can use the command FETCH for it, it work's just like PULL but instead of downloading and merging, it will download it and be stored upon to check

**THIS CHANGE WILL BE DONE WITHIN GITHUB AND FETCHED ON TO THE CODE FOR TEST**

# Learning about new branches

In this case, imagine that you and your friend are working on a project, but in the middle of the project both of you have different ideas on different spots of your code, both of you can work on each desired content and implement new things, and afterwards, merge it all together to create a new branch, the versions of it, will still be saved upon add, staging and commiting to the code. Upon checking the "testing" branch, you'll see about different branches and codes that can be on different versions of it.