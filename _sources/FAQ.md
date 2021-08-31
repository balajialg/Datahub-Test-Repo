# Frequently Asked Questions

```{tabbed} Onboarding new users to the Hub:
1. What are the varied resources that I can review to onboard myself?

If you are new to Datahub and are interested to know more about the configuration used by various Berkeley organizations, you can refer to this documentation available https://docs.datahub.berkeley.edu/en/latest/

If you want to set up a hub infrastructure at your end and are interested to learn more about the technical details behind the set up then use this link https://zero-to-jupyterhub.readthedocs.io/en/latest/

2. What programming languages are supported by the hub?

Datahub primarily supports three languages - Python, R and Julia. However, we can also support other languages on a case to case basis. Please do raise an github issue or send us an email to xxx to share your exact requirement.

3. How many hubs across the campus exist? Which courses use them extensively?

Currently, We have 15+ hubs that caters to the diverse needs of our campus audience. This includes Datahub which is has the maximum number of courses/users. In addition, We have Data 8 hub, Data 100 hub, Biology hub etc.. serving the needs of teaching team and students enrolled as part of Data 8, Data 100 and Biology courses respectively.

You can learn more about the hubs deployed through this link here (https://docs.datahub.berkeley.edu/en/latest/users/hubs.html)

4. What is the default Memory/CPU requirement for every hub?

By default our hubs offer 1 GB RAM. However, if your class/research requires more complex computation then please do reach out to us.

5. What are the different services offered as part of the Datahub?

You can learn more about the varied services through the documentation here (https://docs.datahub.berkeley.edu/en/latest/users/services.html)

6. What are the packages pre-installed for every hub?

Package requirement varies across every hub. We ensure that the basic packages such as Numpy, pandas, scikit-learn etc.. are installed across all the hubs

7. What is the process to raise Github issues? How can I track the raised issues?

If you want to raise a bug currently, you can use this link (https://github.com/berkeley-dsep-infra/datahub/issues/new/choose)to raise the issues

You can also use post messages to our Piazza channel to raise further queries 

8. When do I receive a response when an issue gets raised?

We currently don't have any kind of SLA with regards to requests from users. However, as a rule of thumb we try to respond to your queries within 1-2 days tie

We will resolve queries related to package installation and admin requests between 1-3 days time

9. Are there existing templates for submitting requests to the infrastructure team?

There are multiple templates available which are summarized below,
i) Issue Tracker: If you found a bug in the workflow and want to raise an issue for the same, then please do use this template to raise an issue
ii) New Enhancement: If you found a new feature/documentation that would help you with the existing workflow then please do use this template to raise an issue
iii) Package Addition/Change request: If you want to install new packages in R/Python/Julia as part of your hub then please do raise a request using this template
iv) Request for RAM: If you want to increase/decrease RAM for your specific hub then please do use this template to request

10. As an instructor, What is the process to create a hub for teaching a course?

We would like to know the exact use case for creating a hub. We generally recommend using the Datahub for teaching purposes if it is a small class size or the computational requirements for your courses/research can be completed with .
```

```{tabbed} Changing existing requirements:
1. What should I do if I want to increase the RAM size in my hub?

Raise an issue using the template here!

2. What should I do if I need more CPU power as part of my hub?

Raise an issue using the template here!

3. What should I do if I want to install more packages? 

Raise an issue using the template here!

4. As an instructor, What should I do if I want to conduct a workshop? Are there any existing hubs that I could repurpose?

Send us an email to this email id with the specific usecase you have in mind. 
We would like to know i) your usecase ii) memory requirement iii) CPU requirement iv) size of the class/user base v) Dataset size vi) Language required

5. As a researcher, What is the process to request a hub focused on research?

Send us an email to this email id with the specific usecase you have in mind. 

6. I am going to run a large dataset for my class. What are the steps I can take to ensure that the hub has the required compute power?

As a rule of thumb, we would recommend following steps.


If these steps are not helpful then we would recommend reaching out to us separaetly

7. What should I do If I want to switch from an existing hub to an R hub?

You can directly use the R Datahub dedicated to serve courses using R. If you have specific requirements then please do reach out to us through email

8. As an instructor, Can I request a custom image with different installation requirements?

We need to know your usecase better
```

```{tabbed} Admin Privileges:
1. What does admin access in the hub mean? 

Admin access provides following features,
1. You can start and stop the server for students part of your dedicated hub
2. You can access the student server having issues and debug their instance

2. How do I get access to the admin view? 
We generally recommend the teaching team have access to the admin view. If you require admin access, please share the email id of users who require admin access and share it with (support email id). 

3. How do I restart my server?
Click on the control panel
Find the user whose server you want to restart. 
Click restart server option

4. How do I stop a student server from the admin view?
Click on the control panel
Find the user whose server you want to stop. 
Click stop server option

Attach screenshots to each required step

```


```{tabbed} Troubleshooting issues in the Hub:
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

1. Go to https://r.datahub.berkeley.edu/user-redirect/tree
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

Raise a github issue for the same! We will keep adding common issues to the FAQ so that you could handle it yourself!

```

```{tabbed}  Building new features in the Hub:	
1. How do I raise a new requirement for the hub?

Raise a new github issue using this link https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=type%3A+enhancement&template=featurerequest.md

Follow the steps outlined as part of the template to request for this enhancement

2. Where will I get updates/notifications about the Datahub feature releases?

We are trying to build a cadence by which send public announcements about feature releases or upgrades going forward. Look forward to emails from datahub-announce going forward!
 
3. How can I collaborate with other users on a notebook at the same time?

Currently, We don't provide options to collaborate with other users through Datahub. However, we are working towards integrating collaborative computing experience through Jupyterhub's Retrolab functionality

4. How can I contribute to the open source community building this tool?

Reach out to us if you want to contribute to this tool. You can read this documentation to get a sense of how to contribute to Datahub specifically (https://docs.datahub.berkeley.edu/en/latest/admins/pre-reqs.html)

```

```{tabbed} Sharing information about the Hub:
1. How do I spread the word about the hub?

2. What are the collaterals that I can use to share the information about the hub?
```

