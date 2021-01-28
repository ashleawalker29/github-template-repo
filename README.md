# GitHub Template Repository

This repository is meant to more easily set up the organization and tracking aspect of GitHub. This
includes setting up all relevant labels for pull requests and issues. There are also templates for
when creating a pull request, bug report, or feature request.

This will assist in cutting down the time needed to initialize a repository and standardize the way
pull requests, issues, and labels are used within the repository. The intent here is to increase
readability, consistency, and documentation within the repo by way of templates.

# Table of Contents
* [Installation](#installation)
* [Labels](#labels)
* [Issue Templates](#issue-templates)
  * [Bug Report Template](#bug-report-template)
  * [Feature Request Template](#feature-request-template)
* [Pull Request Template](#pull-request-template)

# Installation

1. Use this Template Repository
    - To use this template repository, navigate to the home page of this repository and click the
      green `Use this template` button near the top of the page.
    - Create your repository as normal, with all your personal settings -- name, description,
      repo privacy, etc.

2. Set up Probot
    - In order to get [settings.yml](.github/settings.yml) to sync with the GitHub repo and
      standardize the labels, you will need to install the GitHub App named
      [Probot](https://probot.github.io/apps/settings/). After installation, Probot can be
      configured to only have access to specific repositories of your choosing or all of your
      repositories. In order for it to sync your newly made repo, at the very least, Probot will
      need access to that repo. It is up to you to decide if you would like it to access just the
      newly made one, or all repos.

# Labels

All the labels included have been inspired by the article
[Sane GitHub Labels by Dave Lunny](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63).
This way we can more easily differentiate between the type of issue and its status. This adds more
readability to the process. Additionally, you may add more labels for the priority.

For example: `"Priority: P0"`, `"Priority: High"`, etc.

For more examples and an explanation on how to effectively use them to sort through issues and
features, visit
[Sane GitHub Labels by Dave Lunny](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63).

The labels currently created within this repository are as follows:

<img width="473" alt="Screen Shot 2021-01-28 at 10 04 25 AM" src="https://user-images.githubusercontent.com/46981564/106172728-5f5adb80-6150-11eb-95c2-14d3449a179e.png">

# Issue Templates

There are two different kinds of issue templates within this repository -- bug reports and feature
requests. These will appear as templates to choose from when creating a new issue. Simply navigate
to the `Issues` tab within your repo and click the green `New Issue` button.

This will bring you to a new menu that allows you decide between creating an issue from a template,
in this case, between the bug report and feature request templates. You may also click on `Open a
blank issue.` if neither templates apply to your issue.

<img width="878" alt="Screen Shot 2021-01-26 at 3 25 38 PM" src="https://user-images.githubusercontent.com/46981564/105914120-1b01fb00-5feb-11eb-87fb-cc1bbade7607.png">

## Bug Report Template

The bug report template is, as the name suggests, for reporting bugs or abnormal behavior. Once
chosen as the template, you will be brought to another page where you will fill out all of the
appropriate information and then submit the new issue.

Specific information has already been determined to cut out the time needed to spend on creating a
bug report that is consistent with all others found in your repo. The list of predetermined
information is as follows:
- The title supplies the prefix `[BUG]` to help identify the issue as a bug report from a glance.
- The labels are predetermined as the issue type `bug` and having a status of `available`.
- The body of the bug report gives guidance and structure to what the bug report should generally
  look like.

While looking at the bug report, you may notice that there are sentences that are wrapped with
`<!--` and `-->`. These do not need to be removed when finally submitting the new issue, as they
indicate that the sentences are commented out within the markdown language used in creating issues.

The following is an example of the body of a bug report that hasn't been filled in with any
additional information, it just has the template formatting:

<img width="1035" alt="Screen Shot 2021-01-27 at 9 56 25 PM" src="https://user-images.githubusercontent.com/46981564/106091940-97c7ce80-60ea-11eb-98f3-dbfcbc1b059e.png">

## Feature Request Template

The feature request template is, as the name suggests, for requesting new features within the
repository. Once chosen as the template to use, you will be brought to another page where you will
be able to fill out all of the appropriate information and then submit a new issue.

Specific information has already been determined to cut out the time needed to spend on creating a
feature request that is consistent with all others found in your repo. The list of predetermined
information is as follows:
- The title supplies the prefix `[FEATURE]` to help identify the issue as a feature request from a
  glance.
- The labels are predetermined as the issue type `enhancement` and having a status of `available`.
- The body of the feature request gives guidance and structure to what the feature request should
  generally look like.

While looking at the feature request, you may notice that there are sentences that are wrapped with
`<!--` and `-->`. These do not need to be removed when finally submitting the new issue, as they
indicate that the sentences are commented out within the markdown language used in creating issues.

The following is an example of the body of a feature request that hasn't been filled in with any
additional information, it just has the template formatting:

<img width="801" alt="Screen Shot 2021-01-28 at 9 32 39 AM" src="https://user-images.githubusercontent.com/46981564/106168810-efe2ed00-614b-11eb-93c6-4f7ff8b075e1.png">

# Pull Request Template

The Pull Request Template is, as the name suggests, used when creating a new pull request. This will
automatically be used for every pull request, you do not get to choose between different types.

To view more information based on the markdown, see the file
[pull_request_template.md](.github/pull_request_template.md). You may notice that there are
sentences that are wrapped with `<!--` and `-->`. These do not need to be removed when finally
creating the new pull request, as they indicate that the sentences are commented out within the
markdown language used in creating the bodies of the pull request.

The following is an example of the body of a pull request that hasn't been filled in with any
additional information, it just has the template formatting:

<img width="1035" alt="Screen Shot 2021-01-27 at 9 26 48 PM" src="https://user-images.githubusercontent.com/46981564/106090212-e7a49680-60e6-11eb-9fe4-180bc21599ef.png">
