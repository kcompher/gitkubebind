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


# let's start with some examples of what we want to do with Binder

## Share computing environments
- [Deploy a reproducible R Studio session for a data scientist to do new work in](https://mybinder.org/v2/gh/binder-examples/r/master?urlpath=rstudio)
  - Can on demand RStudio served via binder effectivity replace a standing RStudio server?
- [Deploy a reproducible Jupyter sessino for a data scientist to do new work in](https://mybinder.org/v2/gh/binder-examples/r/master?filepath=index.ipynb)

## Share reproducible research
- [Shar ](https://mybinder.org/v2/gh/dtak/rrr/master?urlpath=lab)

## Deploy apps
- [Deploy an R Shiney app](https://mybinder.org/v2/gh/binder-examples/r/master?urlpath=shiny/bus-dashboard/)
- [How about scaling an app already written in jupyter notebooks... checkout appmode](https://mybinder.org/v2/gh/binder-examples/appmode/master?urlpath=apps%2Findex.ipynb)
- [i like to draw systems](https://mybinder.org/v2/gh/kmader/jupyterlab-drawio/master?urlpath=lab)
- [i also like to present](http://mybinder.org/v2/gh/binder-examples/jupyter-rise/master?filepath=index.ipynb)

http://mybinder.org/v2/gh/binder-examples/jupyter-rise/master?filepath=index.ipynb

# What does a binder user need?
- Binderhub API
- python, R, js repos?
- container registry
- gitlab or github

## When binder can do it for analytic users, what about developers and 


# let's start with some examples of what we want to do with Gitlab
- interface to kubernetes


# What would be needed to run this disconnected in the enterprise?
- internal Container Registry (served in gitlab)
- other internal Repos?
- internal kube cluster 
- awesome developer/integrator (...**MEGA-MIDAS!**)

