# GAE SKELETON

Google App Engine is a web framework and cloud computing platform for 
developing and hosting web applications in Google-managed data centers

Google App Engine Standard Environment offers a lot of build-in features that
helps in writing web application. 

The skeleton project is proposing structure that can be use to serve: website,
rest api, cms or all of them at once from single project. It comes as well
with some helpful commands and patterns for creating separate config for 
production, staging and local environments

To create new app just clone this repository open Makefile and change 
APP_ID, SDK_PATH to your own and run:

```
rm .git
git init
git commit --allow-empty -m 'Initial commit'
git add .
git commit -m 'Initial project structure'
make build
make run
```
