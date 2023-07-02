# github-actions-list
A list of all the open-source github actions I've worked on and their usage.

## Actions:
https://github.com/okHadi/ga-ssh
### 1- ga-ssh
Workflow to ssh into a github runner.
#
https://github.com/okHadi/notify-slack-workflow
### 2- notify-slack-workflow
Workflow that sends a message to slack whenever another workflow has run for more than x minutes.
#
https://github.com/okHadi/get-IPsets-WAF/
### 3- get-IPsets-WAF
Consists of two workflows. The first workflow adds an IP to a provided IPset in AWS WAF. The second workflow then fetches all the IPs in the provided IPsets and displays them on a react website using github pages. The react website is provided in the repo.
#
https://github.com/okHadi/actions-branch-name-fail
### 4- actions-branch-name-fail
A github actions workflow to check the current branch name, validate it according to a defined regex pattern in order to have the pull request allowed to be merged.
#
https://github.com/okHadi/run-ECSTask-Action
### 5- run-ECSTask-Action
A github actions workflow to run an AWS ECS Task. It also pushes the container to ECR first and then runs a ECS task from that new container. Assumptions are defined in the readme file.
#
https://github.com/okHadi/GA-run-changed
### 6- GA-run-changed
A github actions workflow that only runs only if changes are made in a specified directory.
#
https://github.com/okHadi/block-ip-waf
### 7- block-ip-waf
Similar to number 3, this workflow only consists of one that adds an IP to a given IPset in AWS WAF.
#
https://github.com/okHadi/transfer-linux
### 8- transfer-linux
Github actions to transfer react build files to a remote server. Can be used to transfer any files.
#
https://github.com/okHadi/git-actions-md
### 9- git-actions-md
Github actions workflow that verifies that the README.md file has an appropiate length of titles and their descriptions.
#
https://github.com/okHadi/purge-sqs-queue
### 10 - purge-sqs-queue
A github actions workflow that purges a AWS SQS Dead Letter Queue. Need to provide the Queue URL for it to happen
#

