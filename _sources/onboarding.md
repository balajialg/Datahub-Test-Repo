# Onboarding new users to the Hub

```{note}
Are you new to Datahub? Do you want to learn more about the services offered by the hub? If yes, Do refer below!

```

**What are the varied resources that I can review to onboard myself?**

If you are new to Datahub and are interested in learning more about the configuration of various Berkeley hubs, you can refer to this [resource](https://docs.datahub.berkeley.edu/en/latest/). If you want to set up a hub infrastructure at your end and are interested in learning more about the technical details, use this [resource](https://zero-to-jupyterhub.readthedocs.io/en/latest/).

**What languages are supported by the hub?**

Datahub primarily supports three languages - **Python, R and, Julia**. However, We can also support other languages on a case-to-case basis. If you have a unique requirement for using a different programming language as part of the hub, Please share your requirement over an email to ds-infrastructure@lists.berkeley.edu or raise a Github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose).

**How many hubs across the campus exist? Which courses use them extensively?**

We have 15+ hubs that cater to the diverse needs of the campus audience. We have the main Datahub, which serves multiple courses/departments across the campus. In addition, We have separate hubs for courses such as Data 8, Data 100, Public health, etc., serving the teaching team's needs and enrolled students. You can learn more about the varied hubs deployed through this [link](https://docs.datahub.berkeley.edu/en/latest/users/hubs.html).

**What is the default Memory/CPU requirement for every hub?**

Our default hub Datahub has 1 GB of RAM. However, please reach out to us if your course/research has more complex computation requiring increased RAM.

**What are the different services offered as part of the Datahub?**

You can learn more about the varied services offered through  this jupyterhubs [documentation](https://docs.datahub.berkeley.edu/en/latest/users/services.html).

**What are the packages pre-installed for every hub?**

Package requirement varies across the different hubs. We ensure that basic python packages such as NumPy, pandas, scikit-learn, matplotlib, etc., are installed across all the Jupyter hubs. Our R hubs also support shiny, dplyr, tidyR, RSQLlite, etc. However, you can customize the packages for the hubs by requesting them using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y).

**What is the process to raise Github issues? How can I track the raised issues?**

If you want to raise a bug, you can use this [link](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose) to submit your issues. You can also use post messages to our [Piazza channel](https://piazza.com/class/ksqmnrrhvcl11f) to raise further queries!

**When do I receive a response when an issue gets raised?**

We currently don’t have any Service Level Agreement (SLA) concerning varied requests from users. However, we try to respond to your queries within 1-2 days. In the upcoming days, we will also define an SLA for basic requests such as package requests, admin access, data retrieval, etc.

**Are there existing templates for submitting requests to the infrastructure team?**

You can refer to the following templates for varied use-cases,

**Issue Tracker:** 
Please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=bug&template=bug_report.yml) to raise an issue if you found a bug in the workflow.

**New Enhancement:** If you envision a new feature/documentation that would help your existing workflow, please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=type%3A+enhancement&template=featurerequest.md) to submit a request.

**Package Addition/Change request:** If you want to install new packages in R/Python/Julia as part of your hub, please raise a request using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=higher-resources.md&title=Request+more+RAM+for+class+X).

**Request for RAM:** If you want to increase/decrease RAM for a specific hub then please use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y) to make the request.

**As an instructor, What is the process to create a hub for teaching a course?**

We generally prefer that you use our existing hubs for your work as they already cater to diverse use cases. You can use the Datahub for teaching purposes if you have small class size and/or the computational requirements for your courses and/or research are not complex. If you have genomic data and require complex computations, we recommend using other hubs such as Biology. You can contact us for more details!
