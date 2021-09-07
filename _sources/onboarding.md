# Onboarding new users to the Hub

```{note}
Are you new to Datahub? Do you want to learn more about the services offered by the hub? If yes, refer below!

```

**What are the varied resources that I can review to onboard myself?**

If you are new to Datahub and are interested in learning more about the configuration of various Berkeley hubs, you can refer to this [resource](https://docs.datahub.berkeley.edu/en/latest/). If you want to set up a hub infrastructure at your end and are interested in learning more about the technical details, use this [resource](https://zero-to-jupyterhub.readthedocs.io/en/latest/).

**What languages are supported by the hub?**

Datahub primarily supports three languages - **Python, R and, Julia**. However, We can also support other languages on a case-to-case basis. If you have a unique requirement for using a different programming language as part of the hub, Please share your requirement over an email to Eric Van Dusen (ericvd@berkeley.edu)/Balaji Alwar (balajialwar@berkeley.edu) or raise a Github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose).

**How many hubs across the campus exist? Which courses use them extensively?**

We have 15+ hubs that cater to the diverse needs of the campus audience. We have the main Datahub, which serves multiple departments/courses across the campus. In addition, We have separate hubs for courses such as Data 8, Data 100, Public health, etc., serving the teaching team's and enrolled students needs. You can learn more about the varied hubs deployed through this [link](https://docs.datahub.berkeley.edu/en/latest/users/hubs.html).

**What is the default Memory/CPU requirement for every hub?**

Our default hub Datahub has a memory limit of 1 GB of RAM. However, please contact us if your course/research has more complex computation requiring increased RAM.

If you are interested to know more about how much memory was consumed by your instance or whether you had exceeded the memory limit, Please use the following steps,

- Look at the top right corner of your Python/R notebook for the term memory. It will highlight the amount of memory you had consumed by the amount of memory provided to your instance. 
- If your consumed memory is greater than available memory for your instance, then please do reach out to us,

```{figure} images/memory.png
:width: 500px
align: center
:name: Available Memory

Here is how where you can find the memory related details!
```


**What are the different services offered as part of the Datahub?**

We offer UI for Classic Jupyter Notebook, RStudio and JupyterLab across different hubs. You can learn more about the varied services offered through this jupyterhubs [documentation](https://docs.datahub.berkeley.edu/en/latest/users/services.html).

**What are the packages pre-installed for every hub?**

Package requirement varies across the different hubs. We ensure that basic python packages such as NumPy, pandas, scikit-learn, matplotlib, etc., are installed across all the Jupyter hubs. Our R hubs also support shiny, dplyr, tidyR, RSQLlite, etc. However, you can customize the packages for the hubs by requesting them using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y). We will respond to your requests within three working days.

**What is the process to raise Github issues? How can I track the raised issues?**

If you want to raise a bug, you can use this [link](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose) to submit your issues. You can also use post messages to our [Piazza channel](https://piazza.com/class/ksqmnrrhvcl11f) to raise further queries!

**When do I receive a response when an issue gets raised?**

We currently don’t have any Service Level Agreement (SLA) concerning varied requests from users. However, we try to respond to your queries within 1-2 days. In the upcoming days, we will also define an SLA for basic requests such as package requests, admin access, data retrieval, etc.

*Tentative SLA for varied requests*
- SLA for package installation: All requests will be acknowledged within three working days
- SLA for admin access: Within two working days
- SLA for data archival request: Within three working days
- SLA for RAM increase (if the team validates the raised request): Within three working days

**Are there existing templates for submitting requests to the infrastructure team?**

You can refer to the following templates catering to varied scenarios,

**Issue Tracker:** 
Please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=bug&template=bug_report.yml) to raise an issue if you found a bug in the workflow.

**New Enhancement:** If you envision a new feature/documentation that would help your existing workflow, please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=type%3A+enhancement&template=featurerequest.md) to submit a request.

**Package Addition/Change request:** If you want to install new packages in R/Python/Julia as part of your hub, please raise a request using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=higher-resources.md&title=Request+more+RAM+for+class+X).

**Request for RAM:** If you want to increase/decrease RAM for a specific hub then please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y) to make the request.

** Request to recover hub data:** If you want to request data stored as part of your hub instance, then please do use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=data_archival_request.yml) to raise a request

**As an instructor, What is the process to create a hub for teaching a course?**

We generally prefer that you use our existing hubs for your work as they already cater to diverse needs. 

- You can use the Datahub for teaching purposes if you have small class size and/or the computational requirements for your courses and/or research are not complex. 
- If you have genomic data and require complex computations, we recommend using other hubs such as Biology. 
- You can use EECS hub if you require postgres database service. 

You can contact reach out to Eric Van Dusen (ericvd@berkeley.edu)/Balaji Alwar (balajialwar@berkeley.edu) for more details!