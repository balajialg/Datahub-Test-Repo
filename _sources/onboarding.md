# Onboarding new users to the Hub

```{note}
Are you new to Datahub? Do you want to learn more about the services offered by the hub? If yes, Do refer below!

```

** What are the varied resources that I can review to onboard myself? **

If you are new to Datahub and are interested to learn more about the configuration used by various Berkeley organizations, you can refer to this [documentation](https://docs.datahub.berkeley.edu/en/latest/)

If you want to set up a hub infrastructure at your end and are interested to learn more about the technical details behind the set up then use this [documentation](https://zero-to-jupyterhub.readthedocs.io/en/latest/)

** What programming languages are supported by the hub? **

Datahub primarily supports three languages - Python, R and Julia. We can also support other languages on a case to case basis. If you have an unique requirement, Please do send us an email to ds-infrastructure@lists.berkeley.edu raise an github [issue](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose) to share your exact requirement.

** How many hubs across the campus exist? Which courses use them extensively? **

Currently, We have 15+ hubs that caters to the diverse needs of the campus audience. This includes main Datahub which supports multiple courses/departments. In addition, We have seperate hubs for Data 8, Data 100, Biology etc.. serving the needs of teaching team and enrolled students.

You can learn more about the varied hubs deployed through this [link](https://docs.datahub.berkeley.edu/en/latest/users/hubs.html)

** What is the default Memory/CPU requirement for every hub? **

By default our hubs have 1 GB RAM. However, if your course/research has more complex computation requiring increased RAM then please do reach out to us.

** What are the different services offered as part of the Datahub? **

You can learn more about the varied services offered hrough this [documentation](https://docs.datahub.berkeley.edu/en/latest/users/services.html)

** What are the packages pre-installed for every hub? **

Package requirement varies across the different hubs. We ensure that basic python packages such as numpy, pandas, scikit-learn, matplotlib etc.. are installed across all the Jupyter hubs. Our R hubs also support shiny, dplyr, tidyR, RSQLlite etc.. 

However, you can customize the packages for the hubs by requesting them using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y)

** What is the process to raise Github issues? How can I track the raised issues? **

If you want to raise a bug currently, you can use this [link](https://github.com/berkeley-dsep-infra/datahub/issues/new/choose) to raise your issues

You can also use post messages to our [Piazza channel](https://piazza.com/class/ksqmnrrhvcl11f) to raise further queries!

** When do I receive a response when an issue gets raised? **

We currently don't have any kind of SLA with regards to varied requests from users. However, as a rule of thumb, we try to respond to your queries within 1-2 days. 

We will also define a SLA for basic requests such as package requests, admin access etc.. in the upcoming months

** Are there existing templates for submitting requests to the infrastructure team? **

There are multiple templates available which are summarized below,

**Issue Tracker:** If you found a bug in the workflow and want to raise an issue for the same, then please do use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=bug&template=bug_report.yml) to raise an issue

**New Enhancement:** If you envision a new feature/documentation that would help your existing workflow then please do use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=type%3A+enhancement&template=featurerequest.md) to raise a feature request

**Package Addition/Change request:** If you want to install new packages in R/Python/Julia as part of your hub then please do raise a request using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=higher-resources.md&title=Request+more+RAM+for+class+X) to make the package requests

**Request for RAM:** If you want to increase/decrease RAM for a specific hub then please do use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y) to make the request

* As an instructor, What is the process to create a hub for teaching a course?

We generally prefer that you use our existing hubs for your work. You can use the Datahub for teaching purposes if you have a small class size and/or the computational requirements for your courses and/or research can be completed with existing RAM/CPU requirement. However, if you are interested to create a new hub then we would like to know the exact use case for creating a new hub.
