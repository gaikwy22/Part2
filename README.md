# Part2

## Step 1: 
Add Jenkins Webhook in Github repository with GitHub webhook path at the end of the URL — https://${jenkins_url}/${job-name}/

## Step 2:
Create a new Jenkins job of type "Pipeline"

## Step 3:
Specify the path to Jenkinsfile provided in Pipeline1/Pipeline2 folder. OR Paste the pipeline script in Jenkins job directly.

## Step4:
Run Jenkins job for Pipeline2. Jenkins job for Pipeline1 will be triggered automatically when changes are pushed to Git repository "Part1"
