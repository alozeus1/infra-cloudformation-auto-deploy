# infra-cloudformation-auto-deploy-enterprise

This repository contains CloudFormation templates and GitHub Actions workflow to automate deployment of stacks from GitHub → AWS → Slack.

## Features

- CloudFormation Change Sets (safe previews before applying)
- Slack Notifications on Success
- SNS Notifications on Failure
- Parameterized bucket name
- Git Push → Auto deployment

## Setup

Add these GitHub Secrets:
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_REGION
- SLACK_WEBHOOK_URL

Update SNS Topic ARN in deploy.yml (for failure notification).
