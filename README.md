remote-task-workstation
=======================

Installation
============

### Requirements

- OS

    Ubuntu 12.04 or later

- Git

        $ [sudo] apt-get install git

- Python environment and virtualenv

        $ [sudo] apt-get install python-pip python-dev
        $ [sudo] pip install virtualenv

- Necessary tools

        $ [sudo] apt-get install expect graphicsmagick

- Java 7

        $ [sudo] apt-get install openjdk-7-jdk

    Java version switch `update-alternatives --config java`

- Android SDK

    Follow [Get the Android SDK](http://developer.android.com/sdk/index.html) to install android sdk.

    Note: Don't forget to add `adb` in your path environment.


### Nodejs Runtime

Install it from [Nodejs Official site](http://nodejs.org/), or via [nvm](https://github.com/creationix/nvm).

Note: Nodejs version should >= v0.10.*


### Clone and Install nodejs packages

        $ git clone https://github.com/xiaocong/remote-task-workstation && cd remote-task-workstation
        $ npm install

Run
===

### Run the workstation in private mode

Only you can use the device.

        $ REG_USER=user@email.com ./node_modules/.bin/coffee app.coffee

### Run the workstation in public mode

Share your device with others. 

        $ ./node_modules/.bin/coffee app.coffee

Opentest
===

### [Opentest](http://opentest.io) is a web server to help you

- Manage your test project, task and jobs

- Share your test

- Monitor your test device with terminal output and screen snapshot

- Test result with screen snapshot and logs

### Register and Login

Support github account.

### Project

Create your own project to manage test.

![project](https://github.com/shaofang/remote-task-workstation/raw/develop/docs/img/project.jpg "project")

### Tasks

- Create task

- Share the tasks in the project by adding members

- Stop and re-start task

![task](https://github.com/shaofang/remote-task-workstation/raw/develop/docs/img/tasks.jpg "task")

### Create Task

- Specific Model

- Specific devices 

![createtask](https://github.com/shaofang/remote-task-workstation/raw/develop/docs/img/createtask.jpg "createtask")

### Jobs

- Stop and re-start jobs

- Monitor the specific device with screen snapshot and logs

- Test result of jobs. 

![job](https://github.com/shaofang/remote-task-workstation/raw/develop/docs/img/jobs.jpg "job")

### Monitor

![monitor](https://github.com/shaofang/remote-task-workstation/raw/develop/docs/img/monitor.jpg "monitor")