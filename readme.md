# GitLab Pipelines

This repository contains the configuration for our GitLab CI/CD pipelines.

## Directory Structure

- `Java-maven-aws-docker/`: Contains the pipeline configuration for our Java Maven AWS Docker project.
- `Java-maven-on-premise-docker-k8s/`: Contains the pipeline configuration for our Java Maven On-Premise Docker Kubernetes project.

## Pipeline Configuration Files

- `.gitlab-ci.yaml`: This is the main pipeline configuration file. It defines the stages of the pipeline and the jobs that run at each stage.
- `.gitlab-ci2.yaml` and `.gitlab-ci3.yaml`

## Usage

To run a pipeline, push your changes to the repository. GitLab will automatically detect the pipeline configuration files and run the pipeline.
