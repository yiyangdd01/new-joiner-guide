# What`s you need to pay attention in your dev work

### ⚠️ 1、Please confirm the design before development

Sometimes, the design is not frozen, you need to confirm the design is frozen or not to avoid wasting your work.

### ⚠️ 2、Once your PR is merged, change the ticket status on JIRA in time

You should update your development info in time to let your teammate get the development status in workflow. 

### ⚠️ 3、Respond the bug & doubt in channel which is related to you in time

The **QA** and **User** will have some **doubts** or report **bugs** of the product which is related to you. You should have a response in the channel. If it`s a doubt, please answer the inquirer.  If It is a bug, You should tell the reporter you will check it as soon or give the reason for the bugs if you can, and then you should find the reason for the bugs and fix them as soon. In short, don`t be 'quiet' with the inquirer in the channel !

### ⚠️ 4、You should think a little more when you doing a task

This will **help** your development work **stable**, you should **think more** about the details when you **doing** a **task**, because the task may have some **hidden** **problems**. If you find some **doubts** and think it is **weird** or it may have some **changes** after the task is **done**, You should **communicate** with your teammates **in time** to confirm the **solution**.

### ⚠️ 5、Deploy the Beta version as soon

If QA **confirmed** the Beta can be deployed **after** check the **pre env**(alpha or staging), you should deploy the Beta version **as soon**.

### ⚠️ 6、Remember to add JIRA ID in you PR title  or your commit

You should fill content as `type(scope?): [${group}-${JIRA-ID}] ${subject}` of PR title, It`s help to follow your task and let the viewer known the details of your task.

### ⚠️ 7、A good end in each deploy stage

There has a **Release** **CheckList** of Issues Template in each Repo, you can know what you should do in **each** **deploy** **stage**, So The good beginning should be ended with a good ending, **Don`t** **forget** some **steps** in your release.    

### ⚠️ 8、Ensure your PR don`t be large

The large PR will cause some problems. **First and most important,** it will be more hart to review, too many CL will cause the CR** quality is not well**, it`s also will **cost more time** to check is your CL has effects in other features. Second, if the CL is too many, it may have many commits, so squash merge or not is hard to decide and it`s will lose the key commit in the PR. Please split your feature more small as much as possible。By this way, it will improve the PR`s quality and the development efficiency。

