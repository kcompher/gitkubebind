# gitkubebind
demo on why i like gitlabe, kubernetes, jupyter and binder 

## How amazing is this technology! 
Let me explain why I love DEVOPs/DATAOPs integrations with gitkubebind


## Why Binder?
Binder allows you to create custom computing environments that can be shared and used by many remote users.
It is powered by BinderHub, which is an open-source tool that deploys the Binder service in the cloud.

## Why Kube?
Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.
It groups containers that make up an application into logical units for easy management and discovery. Kubernetes builds upon 15 years of experience of running production workloads at Google, combined with best-of-breed ideas and practices from the community.

## Why Gitlab?
GitLab is the leading integrated product for modern software development. Connecting issue management, version control, code review, CI, CD, and monitoring.. Oh & it has awesome integrations with Kube


# let's start with some examples of what we want to do

- [Deploy an R Shiney app](https://mybinder.org/v2/gh/binder-examples/r/master?urlpath=shiny/bus-dashboard/)
- [Deploy a reproducible R Studio session for a data scientist to do new work in](https://mybinder.org/v2/gh/binder-examples/r/master?urlpath=rstudio)
  - Can on demand RStudio served via binder effectivity replace a standing RStudio server?
- [Deploy a reproducible Jupyter sessino for a data scientist to do new work in](https://mybinder.org/v2/gh/binder-examples/r/master?filepath=index.ipynb)

# What would be needed to run this disconnected in the enterprise?
- internal Container Registry (served in gitlab)
- internal kube cluster 
- awesome developer/integrator (...**team MIDAS**)
