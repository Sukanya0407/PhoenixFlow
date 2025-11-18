# POSTMAN API AUTOMATION INTEGRATION WITH API TESTS #
This repository is demostration for POC for integrating postman tests with github actions.The tests are written in Postman and executed in VM with help of newman and newman-reporter-htmlextra.
Github action will trigger the project execution on every push to the main branch.You can also execute the project manually using workflow_dispatch.This project runs on scheduled time with help of cron jobs.

The HTML repost is archived and kept in artifact section for the team to download it.Along with that they can view report directly from Github page:https://github.com/Sukanya0407/PhoenixFlow.
Latest report is mailed  using GMAILSMTP.

##TECH-STACK##
1)Postman
2)NodeJS 22v
3)Newman
4)Newman-reporter-htmlextra
5)Gmail SMTP
6)Github Actions
7)Github Pages
8)CSV for Data Driven Testing

##TEST-COVERAGE##
1)Happy Flow Testing
2)Negative Testing
3)Token Testing
4)Data Testing with CSV
5)Scheman Validation
6)Secret Managemnt with Github Secrets

#how to run the project?#

1)You can clone the Project:https://github.com/Sukanya0407/PhoenixFlow.git
2)Install Nodejs and NPM.
3)Install Newman using npm install -g newman
4)Install newman-reporter-htmlextra

#HTML REPORT#
Report will be created in Newman folder

