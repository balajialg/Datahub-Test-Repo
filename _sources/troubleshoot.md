# Troubleshooting issues in the Hub

```{note}
Are you facing issues with the Datahub and want to do some troubleshooting? If yes, read below!

```

**What should I do if my hub is running slow?**

Try these options and see if the hub speed improves,

- Restart your kernel if your hub is running slow

- Check whether there are lot of open tabs? If yes, close the tabs that are not required.

If you still face the issue, raise a [bug](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=bug&template=bug_report.yml)!

**What should I do if my code is running slow?**

In general, it could be attributed to the varied programming practices adopted that might have slowed the operation of the hub. Check whether your code does any of the following, 
1. You are running an infinite loop 
2. Your computation/calculation is big 
3. You are joining tables that are too large
4. You have too many notebooks open at the same time
5. You are trying to show a table which is too large and as a result are crashing the browser

If none of the highlighted points seem relevant in your scenario, Please raise a bug request!

**What should I do if I get "503 service unavailable error" regularly?**

This error could be due to some of our stability improvements. Try restarting your server and wait for few minutes to see whether the issue still persists. If yes, raise a github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose).

**What should I do if I get "403 errors: Blocking request from unknown origin" regularly?**

Sorry, that you had to face this error. This error could be due to multiple reasons outlined below, 

- You are using a different domain other than berkeley.edu which could have potentially raised this issue. Raise a github issue, so that we can authorize your domain.

- Large number of your students are trying to use the service resulting in failure of certain nodes. We are working on improving how we scale the hub with large volume of users.

Please raise a github issue!

**What should I do if I get an “An unknown error occurred while loading this notebook” as part of the datahub service?**

Try opening a new terminal from the instance and run the following command, 

```python
rm -f ~/.local/share/jupyter/nbsignatures.db
```

If the issue still persists, raise a github issue.

**What should I do if there is a package conflict?**

[Get inputs from the team]
Try to move to the previous version of the package to see if the conflict exists. If it still exists, try resolving the dependencies manually by installing the required packages. 

**What should I do if my kernel dies?**

As a rule of thumb, restart the kernel whenever it dies. This should work for the most cases.

**What should I do if I am getting RStudio Initialization Error: Error occurred during transmission error.**

Please follow this workaround until a fix can be identified and implemented. Workaround involves renaming or removing ~/.rstudio via the terminal. To do so while bypassing the typical rstudio session startup:

1. Go to this [link](https://r.datahub.berkeley.edu/user-redirect/tree)
2. Click New->Terminal
3. In the terminal, type: mv .rstudio .rstudio.$(date +%s) and press return
4. Try to launch rstudio as you normally would and it should now work.

**What should I do if R Studio times out and kicks me out every 5 minutes or so?**

[Get inputs from team on how to handle this scenario]

**What should I do if I have an issue that has not been documented in the FAQ?**

Raise a github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose)! We will keep adding common issues to this FAQ!
