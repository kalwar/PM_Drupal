# Customer Portal

Customer portal using OpenLucius Drupal module. The goal is to be easy-to-use software that helps your people to communicate better, manage knowledge, build culture, get projects done, share and manage (large) files, and more.

Goal is also to create an optimal developer -and site builder experience for building add-on modules and easy management / updates.

![Alt text](/screenshot.png?raw=true "Optional Title")

## Installing OpenLucius

Install it using Composer:

```
composer create-project lucius-digital/openlucius-project:2.0.0-beta1 MY_PROJECT_FOLDER
cd MY_PROJECT_FOLDER
copy .env_example to .env
docker-compose up
```

## Optional project content

The project also contains these optional packages:

- a ready-made Docker environment;
- a Node.js package, optionally needed for realtime goodies like the chat.

## Troubleshooting

You have to install certificates for running it locally using docker

- https://www.getlucius.com/en/product/open-source-install-guide-docker
