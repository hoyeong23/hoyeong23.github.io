---
title: Getting Started
author: cotes
date: 2019-08-09 20:55:00 +0800
categories: [Blogging, Tutorial]
tags: [getting started]
pin: true
---

## Installation

### Creating a New Site

There are two ways to create a new repository for this theme:


#### Option 2. GitHub Fork


Before running local server for the first time, go to the root directory of your site and run:

### Configuration

- `url`
- `avatar`
- `timezone`
- `lang`

### Social Contact Options



### Running Local Server

You may want to preview the site contents before publishing, so just run it by:


Now you can choose _ONE_ of the following methods to deploy your Jekyll site.


Next, configure the _Pages_ service.

1. Browse to your repository on GitHub. Select the tab _Settings_, then click _Pages_ in the left navigation bar. Then, in the **Source** section (under _Build and deployment_), select [**GitHub Actions**][pages-workflow-src] from the dropdown menu. 

2. Push any commits to GitHub to trigger the _Actions_ workflow. In the _Actions_ tab of your repository, you should see the workflow _Build and Deploy_ running. Once the build is complete and successful, the site will be deployed automatically.

At this point, you can go to the URL indicated by GitHub to access your site.

### Manually Build and Deploy

On self-hosted servers, you cannot enjoy the convenience of **GitHub Actions**. Therefore, you should build the site on your local machine and then upload the site files to the server.

Go to the root of the source project, and build your site as follows:
