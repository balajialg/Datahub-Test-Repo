# Onboarding new users to the Hub

```{note}
New to Datahub? Interested to learn more about the services offered by the hub? If yes, refer below!

```

**How can I learn more about Datahub to onboard myself?**

If you are new to Datahub and want to know more, refer to our [website](https://datahub.berkeley.edu/hub/login?next=%2Fhub%2F). If you are interested in learning more about the configuration of various Berkeley hubs, you can refer to this [resource](https://docs.datahub.berkeley.edu/en/latest/). If you want to set up a hub infrastructure at your end and are interested in learning more about the technical details, use this [resource](https://zero-to-jupyterhub.readthedocs.io/en/latest/).

**What languages are supported by the hub?**

Datahub primarily supports three languages - **Python, R and, Julia**. However, We can also support other languages on a case-to-case basis. If you have a unique requirement for using a different programming language as part of the hub, Please share your requirement over an email to Eric Van Dusen (ericvd@berkeley.edu)/Balaji Alwar (balajialwar@berkeley.edu) or raise a Github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose).

**How many hubs across the campus exist? Which courses use them extensively?**

We have 15+ hubs that cater to the diverse needs of the campus audience. We have the main Datahub, which serves multiple departments/courses across the campus. In addition, We have separate hubs for courses such as Data 8, Data 100, Public health, etc., serving the teaching team's and enrolled students needs. You can learn more about the varied hubs deployed through this [link](https://docs.datahub.berkeley.edu/en/latest/users/hubs.html).

**What is the default Memory/CPU requirement for every hub?**

Our default hub Datahub has a memory limit of 1 GB of RAM. However, please contact us if your course/research has more complex computation requiring increased capacity. If you are interested to know more about the memory consumption in your instance, Please use the following steps,

- Look at the top right corner of your Python/R notebook for the term memory. It will highlight the amount of memory you had consumed by the amount of memory provided to your instance. 
- If your consumed memory is greater than the available memory for your instance, You may require an increase in RAM,

```{figure} images/memory.png
:width: 500px
align: center
:name: Available Memory

Here is where you can find the memory related details!
```


**What are the different services offered as part of the Datahub?**

We offer UI for Classic Jupyter Notebook, RStudio and JupyterLab across different hubs. You can learn more about the varied services offered through this jupyterhubs [documentation](https://docs.datahub.berkeley.edu/en/latest/users/services.html).

**What are the packages pre-installed for every hub?**

Package requirement varies across the different hubs. We ensure that basic python packages such as NumPy, pandas, scikit-learn, matplotlib, etc., are installed across all the Jupyter hubs. Our R hubs also support shiny, dplyr, tidyR, RSQLlite, etc. However, you can customize the packages for the hubs by requesting them using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y). Here is the [list](https://github.com/berkeley-dsep-infra/datahub/blob/staging/deployments/datahub/images/default/requirements.txt) of Python packages installed across hubs. Here is the [list](https://github.com/berkeley-dsep-infra/datahub/blob/staging/deployments/datahub/images/default/install.R) of R packages installed across hubs.

**What is the process to raise Github issues? How can I track the raised issues?**

If you want to raise a bug, you can use this [link](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose) to submit your issues. You can also use post messages to our [Piazza channel](https://piazza.com/class/ksqmnrrhvcl11f) if you require real time troubleshooting!

**When do I receive a response when an issue gets raised?**

Please refer to the below Service Level Agreement (SLA) for varied requests. It will be finalized soon,

- SLA for package installation: "Acknowledgement within two working days."
- SLA for RAM increase: "Acknowledgement within two working days."
- SLA for admin access: "Request completed within two working days."
- SLA for data archival request: "Request completed within three working days."

**Are there existing templates for submitting requests to the infrastructure team?**

You can refer to the following templates catering to varied scenarios,

**Issue Tracker:** 
If you found a bug in the workflow, Please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=bug&template=bug_report.yml) to raise an issue.

**New Enhancement:** If you envision a new feature/documentation that would help your existing workflow, please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=type%3A+enhancement&template=featurerequest.md) to submit a request.

**Package Addition/Change request:** If you want to install new packages in R/Python/Julia as part of your hub, please raise a request using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=higher-resources.md&title=Request+more+RAM+for+class+X).

**Request for RAM:** If you want to increase/decrease RAM for a specific hub then please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y) to make the request.

**Request to recover hub data:** If you want to request data stored as part of your hub instance, then please do use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=data_archival_request.yml) to raise a request

**As an instructor what do I need to do to set up the hub for my course?**

Honestly, nothing! You are free to go ahead and start using the Datahub starting today. We expect that all course members log in using their UC Berkeley email id. We also expect that you are using [nbgitpuller service](https://jupyterhub.github.io/nbgitpuller/link) to distribute materials to your class. We can help you set up the links so that you can distribute them through your course website. 

