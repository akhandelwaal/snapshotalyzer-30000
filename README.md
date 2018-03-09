# Snapshotalyzer-30000

Demo Project to manage AWS EC2  instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses configuration file created by the AWS CLI e.g.

'aws configure --profile shotty'

## Running

'pipenv run "python shotty/shotty.py <command> <subcommand>
<--project=PROJECT>"'

*command* is instanes, volumes, snapshots
*subcommand* - depends on command
*project* is optional
