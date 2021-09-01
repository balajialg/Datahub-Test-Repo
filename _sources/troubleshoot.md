# Troubleshooting issues in the Hub:

```{note}
Are you facing issues with the Datahub and want to do some troubleshooting? If yes, read below!
```

1. What should I do if my hub is running slow?

Restart your kernel if your hub is running slow

Check whether there are lot of open tabs? If yes, close the tabs that are not required

2. What should I do if my code is running slow?

Check whether your code does the following, 
1. You are running an Infinite loop 
2. Your computation/calculation is big, 
3. You are joining tables that are too large
4. You have too many notebooks open at the same time
5. You are trying to show a table which is too large and as a result are crashing the browser

3. What should I do if I get "503 service unavailable error" regularly?

This error could be due to some of our stability improvements. 

To start with, Try restarting your server. Wait for sometime to see whether the issue still persists.

If yes, raise a github issue so that we can take a look at it.

4. What should I do if I get "403 errors: Blocking request from unknown origin" regularly?

It could be due to multiple reasons,

You are using a different domain other than berkeley.edu which could have potentially raised this issue. 

Large number of your students are trying to use the service resulting in failure of certain nodes

If that be the case raise a github issue, so that we can authorize your domain.

5. What should I do if I get an “An unknown error occurred while loading this notebook” as part of the datahub service?

Try opening a new terminal from the instance and run the following command, 

rm -f ~/.local/share/jupyter/nbsignatures.db

If the issue still persists, raise a github issue so that we can take a look at it.

6. What should I do if there is a package conflict?



7. What should I do if my kernel dies?

As a rule of thumb, restart the kernel whenever it dies

8. What should I do if I am getting RStudio Initialization Error: Error occurred during transmission error. 

Please follow the workaround until a fix can be identified and implemented. This can be fixed by renaming or removing ~/.rstudio via the termin
al. To do so while bypassing the typical rstudio session startup:

1. Go to this [link] (https://r.datahub.berkeley.edu/user-redirect/tree)
2. Click New->Terminal
3. In the terminal, type: mv .rstudio .rstudio.$(date +%s) and press return
4. Try to launch rstudio as you normally would and it should now work.


9. What should I do if R Studio times out and kicks me out every 5 minutes or so? 


10. What should I do if I get an errors like these below,
	1. While(1);{"error":"invalid_request","error_description":"redirect_uri does not match client settings"}
	2. System has not been booted with systemd as init system (PID 1). Can't operate. Failed to create bus connection: Host is down.
	3. “psql: FATAL: could not write init file” and “psql: .... No space left on device”
	4. "no nodes available" / "insufficient memory" etc. 
	5. “[Normal] Pulling image” 
11. What should I do if I have an issue that has not been documented in the FAQ?

Raise a github [issue] (https://github.com/berkeley-dsep-infra/datahub/issues/new/choose)for the same! We will keep adding common issues to the FAQ so that you could handle it yourself!
