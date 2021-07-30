# Saturday Hack Night Template

TinkerHub saturday hack night submission repository template. 

This repository contains the following GitHub Action workflows:
- Add Project - This will allow organizer to add a new project to the GitHub repository as a submodule so that the project can be evaluated. This contains the following params:
    - Repository URL: URL of the project's repo (HTTPS)
    - Folder Name: You can specify a folder naem to keep the submodule (eg: project name)
- Update Projects - This workflow will run every hour updating the submodules to its latest state. It can be also triggered manually from actions tab.