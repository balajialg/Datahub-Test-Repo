# Changing existing requirements

```{note}
Interested to learn more about how to change the default requirements for your hub? If yes, read below!

```

**What should I do if I want to install more packages?**

- Use your datahub instance to install the required version of the package. 

- If you want to install packages for Python then use the following syntax,

```python
pip install <package-name>
Eg: pip install numpy
```

- If you want to install packages for R then  use the following syntax,

```python
install.packages("<package-name>")
install.packages("ggplot2")
```
- Check if there are specific dependencies for this package. Highlight the  package name along with their version as part of your request. 

- Raise a request using this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=datahub-package-addition---change-request.md&title=Request+python+package+X+for+class+Y)!

**What should I do if I want to increase the RAM size/CPU power in my hub?**

As a first instance we recommend that the instructors adapt the materials to the 1GB requirement of the hub. If you have a compelling use case for more, use this [template](https://github.com/berkeley-dsep-infra/datahub/issues/new?assignees=&labels=support&template=higher-resources.md&title=Request+more+RAM+for+class+X) and provide an explanaiton as it has cost implications for the service.

**As an instructor, What should I do if I want to conduct a workshop? Are there any existing hubs that I could repurpose?**

Please send an email to Eric Van Dusen (ericvd@berkeley.edu)/Balaji Alwar (balajialwar@berkeley.edu) with the specific request you have in mind. We would like to know i) Your exact need, ii) Memory/CPU requirement, iii) Total number of participants, iv) Dataset size, and v) Language required.

**As a researcher, What is the process to request a hub focused on research?**

We offer hubs to support the teaching practices of our instructors. If you are interested to do research then we would recommend you to contact the team at [Research IT](https://research-it.berkeley.edu/). You might benefit from checking out their High Performance Computing Cluster [Savio](https://research-it.berkeley.edu/services-projects/high-performance-computing-savio) and [On Demand Virtual Machines](https://research-it.berkeley.edu/services-projects/aeod-virtual-machines). 

**I am going to run a large dataset for my class. What are the steps I can take to ensure that the hub has the required compute power?**

As a rule of thumb, we recommend the following steps. If these steps are not helpful, then we would recommend reaching out to us separately,

- Github has a file upload limit of 100 MB. We would recommend to keep the size of the dataset below 100 MB for this specific reason. 
 
<- Get team's inputs ->

**What should I do If I want to switch from an existing hub to an R hub?**

You can directly use the [R Datahub](http://r.datahub.berkeley.edu/) dedicated to serving courses using R. If you have other specific requirements, please do reach out to us.

** When can I create a new hub? **

We generally prefer using our existing hubs for teaching your courses. Our guiding principles for allowing the creation of new hub follows below,

- When the course has a large user base

- When there is a need for undergrad admins to have admin access

- When there is a specific technical/architectural reasons

- When there is a strong institutional/strategic reason

**As an instructor, Can I request a custom image with different installation requirements?**

It depends on your requirement. Please do send an email to Eric Van Dusen (ericvd@berkeley.edu)/Balaji Alwar (balajialwar@berkeley.edu) with your detailed requirement.