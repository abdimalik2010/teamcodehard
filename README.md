# aras_u05_sprint1

Work done on sprint one

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/SaraPetre/aras_u05_sprint1.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/SaraPetre/aras_u05_sprint1/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Automatically merge when pipeline succeeds](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing(SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!).  Thank you to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README
Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
This MVP (Minimum Viable Product) is build for a campany which ordered a database model for its webshop us earlier and now wants to move on with the next steps in the development process. 

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.


## Installation

How run the project?

- Create a virtual environment
- python -m venv [directory]
Activate the venv and install requirements
* Mac OS / Linux
- source [your-directory]/bin/activate
* Windows
-- your-directory\Scripts\activate

- Run requirements install pip install -r requirements.txt
- Enter in venv
- Run tests pytest
- pytest test_api.py --cov --cov-report html

## Requirements

You will need to have the following available to work with:

- Docker and docker-compose
- Code editor
- Virtual environment installed requirements and dependencies


## Authors and acknowledgment
Acknowledgements
This project was inspired by our dear teacher Kristian Kjeldsen.

Also in cooperation with Elon Musk and his vision of the future, to mars!


https://www.youtube.com/watch?v=ZBgXb66Ckz0

Contact
Created by Team Codehard:

Jani Karhula (https://github.com/Hessupatteri)

Sara Petre (https://github.com/SaraPetre)

Erik Levander (https://github.com/ErikLevander)

Markus Sköld (https://github.com/MarkuSkold)

Selim Hussen (https://github.com/Selimdinho)

Abdimalik Omar (https://github.com/abdimalik2010)

## License
For open source projects, say how it is licensed.

## Project status

When the app is running you shoule be able to run:


```
Docker-compose up 
```

(If you change something then update the command)

And it should display the same content as running the app with docker-compos
