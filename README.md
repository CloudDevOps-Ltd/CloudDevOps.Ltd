# CloudDevOps.Ltd Website

To install jekyll, first install ruby then run the following command.
`sudo gem install jekyll`

## Run website locally.

To run the website locally, follow below steps. This will Build the site and outputs a static site to a directory called `_site` and then serve the website.
`jekyll build`

`jekyll serve`


GitHub Action pipeline will be triggered as soon as there is a commit to main branch.

Build Status:
[![Docker Image CI](https://github.com/CloudDevOps-Ltd/CloudDevOps-Ltd.github.io/actions/workflows/pages.yml/badge.svg)](https://github.com/CloudDevOps-Ltd/CloudDevOps-Ltd.github.io/actions/workflows/pages.yml)
