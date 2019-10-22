# PR-CR-NOTES
> This part is get your attention when you PR and CR

## What`s you should attention to when PR
### Naming
- ⚠️ PR title should be with JIRA ID and naming.

### Design
- 👏 It is better to have screenshots of prev version and result in PR`s description.

### Travis CI
- ⚠️ Check the CI status, because it failed usually.

### Squash Merge or Merge PR
- ⚠️ Don`t squash merge if the commits need be a part of target branch.

### PR merged
- ⚠️ Please change the relate issue`s status and assignee in JIRA after PR merged immediately.

## What`s you should attention to when CR
> Code review make code better, not best.

### Design
- If you not sure the PR`s deisgn is expect UI design, please pull the branch and check it.
- Is the code make sense?
- Is suitable with other components or librarys?
- Is the change necessary at this point in time?
- Is this part overall or hight level?

### Functional
- Is the code  good to the future developer?
- If you have free time, you should test it by yourself and think seriously about code whether it has some problems.

### Complexity
- Is the code design very complex?
- Is the code over-engineering? should keep it more flexible and readable.

### Naming
- is the code has meaningful names?

### Style
- Is the code followed the Style Guide?

### Doc
- Is doc sync with code if they are relate?

### Comment

- Your comment should be respetc and friendly.
- Explan fully, give the reason of your comment and leave some good pratices if you can.
- Encourage developer simplify code and leave the key or orientation of problem.
- You can think him is right if you agree with developer`s explanation and the PR is not bad to base code.
- You can communicate with developer friendly if you do`nt agree his solutions, but with good comment.

### Good Thing
Code review is not only find error. if the developer`s produce is good, dont save your praise.
- LGTM
- Other praise words

