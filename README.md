# theme: jekyll-theme-minimal
title: Introduction to my website
# mahmut-ozkaya.github.io
title: Introduction to GitHub
description: If you are looking for a quick and fun introduction to GitHub, you've found it. This class will get you started using GitHub in less than an hour.
template:
  name: github-slideshow
  repo: caption-this-template
  description: 'A robot powered training repository :robot:'
preferences:
- type: radio
  name: gitTool
  label: Preferred Git tool
  description: Learn right from the web UI, or using your chosen tool
  options:
  - label: Use the GitHub.com web interface
    value: dotcom
  - label: Use the command line
    value: cli
  - label: Use Visual Studio Code
    value: vscode
- type: dropdown
  name: language
  label: Language
  description: Choose your preferred language.
  options:
  - label: English
    value: en
  - label: Español
    value: es
  - label: 日本語
    value: ja
  - label: Français
    value: fr
before:
- type: updateBranchProtection
- type: createIssue
  title: Getting Started with GitHub
  body: 00_introduction.md
  comments:
    - 00_assign-yourself.md
