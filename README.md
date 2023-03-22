# chatops-slackbot-template

A basic Slackbot built with serverless and Bolt, deployed to AWS Lambda with GitHub Actions.

That's the end-goal at least, for now this is very much a work in progress.

## Deployment

```shell
cd chatops-slackbot
aws-vault exec <profile> --no-session -- sls deploy
```
