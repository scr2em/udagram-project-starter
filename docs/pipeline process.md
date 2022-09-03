# Pipeline Process

The pipeline is set up and connected with this GitHub repository in CircleCI.

## Order of commands

1. The pipeline uses orbs to install Node, the AWS cli and the EB cli.
2. It checks out the code from the repo
3. Frontend install
4. Backend install
5. Frontend build
6. Backend build
7. Frontend deploy
8. backend deploy

## Schema

![Pipeline Schema](./images/pipeline.png)
