# CloudFormation Stack Delete Workflow

This workflow allows manual deletion of the CloudFormation stack using GitHub Actions.

## How to use

1. Go to GitHub → Actions → Delete CloudFormation Stack → Run workflow
2. Type YES in the confirm_delete input field
3. Workflow will trigger and delete the stack

This prevents accidental deletions by requiring confirmation.
