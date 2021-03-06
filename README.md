# Economic Analysis Tools Documentation for Users

[![Build Status](https://travis-ci.com/TransLinkForecasting/econdoc.svg?branch=master)](https://travis-ci.com/TransLinkForecasting/econdoc)
[![RTD Build Status](https://readthedocs.org/projects/rtm/badge/?version=latest&style=flat)](https://readthedocs.org/projects/rtm_econdoc)

This is a mkdocs-generated documentation for the Regional Transportation Model (RTM) by TransLink Forecasting. This repository has been set up with travis ci and readthedoc for automated deployment.

Please visit the documentation on [github.io](https://translinkforecasting.github.io/econdoc) or [readthedoc](https://rtm-econdoc.readthedocs.io).

## Getting Started

As **econdoc** collaborators, you are invited to contribute to the economic analysis documentation for the RTM. This documentation is compiled using [mkdocs](https://www.mkdocs.org/).

Follow the steps below create or update mkdocs-generated html:

### Install prerequisites

* download and install [git](https://git-scm.com/downloads)
* download and install [python anaconda](https://www.anaconda.com/distribution/)
* set up environment with prerequisites:
   * `conda remove --name rtm_docs --all`
   * `conda create -n rtm_docs python=3.6 pip`
   * `conda activate rtm_docs`
   * `pip install -U -r requirements\project.txt`

### Clone rtmdoc and develop

* clone git repository: `git clone https://github.com/TransLinkForecasting/rtmdoc.git`
* test build locally: `mkdocs build`
* test development : `mkdocs serve`
* commit and push your temp branch and create a pull request:
   * `git checkout -b master_pr_num`
   * `git commit`
   * `git push origin master_pr_num`
