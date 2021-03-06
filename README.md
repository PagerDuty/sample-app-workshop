# Sample App Workshop

This simple application runs in an Nginx container. It displays a successful default web page when Nginx is running but the service can be stopped by entering the right word.

## Description

In order to demonstrate a CloudWatch Alarm, this application allows the user to stop the Nginx service through the default web page rather than having to ssh in and stop it.

## Getting Started

### Dependencies

* Python-dotenv
* Gunicorn
* Flask

### Installing

This application is referenced by a CloudFormation template that will install it.  
e.g. [AWS Modernization Workshop](https://github.com/aws-samples/aws-modernization-workshop-sample/blob/master/code-samples/cloudformation/sample-web-app/Demo-noasg.yml)

## Version History

* 0.1
    * Initial Release
* 0.2
    * Upgrade of Flask version
