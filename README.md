# build-and-release-pipelines
i. single-stage-app-pipeline is a single yaml file runs on ado over a react app and deploys artifacts to nginx on a linux VM.

ii. build pipeline is CI pipeline(build and publish artifacts on azure) for react app deployment on webapp.

iii. release pipeline is CD pipeline(download and deploy to webapp) for the previous build pipeline.