# git-learning
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
