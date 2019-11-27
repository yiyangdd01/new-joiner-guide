> This part is getting your attention when you PR or CR and should think more about it 

## 

#  PR

## Naming

- PR title should be with JIRA ID and naming.

## Design

- It`s better to have screenshots of prev version and result in PRs description.

## Travis CI

- Check the CI status, because it failed usually.

## Squash Merge or Merge PR

- Don`t squash merge if the commits need to be a part of the target branch.

## PR merged

- Please change the related issue`s status and assignee in JIRA after PR merged immediately.

#  CR

> Code review make code better, not best.


## Design

- If you not sure the PR`s design is expected, please pull the branch and check it.
- Is the code make sense?
- Is it suitable for other components or libraries?
- Is the change necessary at this time point?
- Is this part overall or hight level?

## Functional

- Is the code good to the future developer?
- If you have free time, you should test it by yourself and think seriously about code whether it has some problems.

## Complexity

- Is the code design very complex?
- Is the code over-engineering? should keep it more flexible and readable.

## Naming

- Is the code has meaningful names?

## Style

- Is the code followed the Style Guide?

## Doc

- Is doc sync with code if they are related?

## Comment

- Your comment should be respect and friendly.
- Explain fully, give the reason for your comment and leave some good practices if you can.
- Encourage developer to simplify code and leave the key or orientation of the problem.
- You can think him is right if you agree with the developer`s explanation and the PR is not bad to base code.
- You can communicate with developer friendly if you don't agree with his solutions, but with good comment.

## Good Thing

Code review is not only found error. if the developer`s produce is good, don't save your praise.

- LGTM
- Other praise words

