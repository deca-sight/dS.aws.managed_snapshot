# dS.aws.managed_snapshot
Manage AWS EC2 snapshots

## About

This project uses boto3 to manage AWS EC2 Instances snapshots

## Configuriong

Uses the configuration file created by the AWS cli. e.g.
'aws configure --profile <profile>'

## Running

'pipenv run "python dS.aws.managed_snapshot/dS.aws.managed_snapshot.py <command> <--project=PROJECT>"'
*command* is list, start, or stop
*project* ist optional
