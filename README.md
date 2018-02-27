# AWS
AWS All

## Running

This Project requires Pyton 3 and the Requests package

First, install pipenv. Then:

```
pipenv install

```
#Configure AWS CLI

`aws configure --profile sdamera`

## Running

`pipenv run "python ec2-list.py <command> <subcommand> <--project=PROJECT>"`

*commands:*
   list List EC2 instances
   start Start EC2 instances
   stop Stop EC2 instances

*subcommand* - depends on command
*project* is optional

