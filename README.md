# Description

This repository contains templates for deploying a High availability Application using AWS Cloudformation.


The infrastructure deployed is described in this [image](https://github.com/duoarc/Deploy-a-High-Availability-Web-App-Using-CloudFormation/blob/master/Infrastructure-diagram.jpeg).

The shell script `create.sh` creates a stack in AWS CLI while the `update.sh` script updates the stack with changes.

Parameters are saved in JSON files while the YAML files are the configuration for the infrastructure. Network infrastructure stack was seperated from the Server Infrastructure stack.

This was a fun and very educative project! :-) 
