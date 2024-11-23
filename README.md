# Building a Secure Golden Image in AWS Cloud

## Description

This project demonstrates how to build a secure golden image in AWS Cloud. A golden image is a pre-configured, secure, and ready-to-use base image that can be deployed across your AWS infrastructure.

The project automates the creation and hardening of the image to ensure compliance with security best practices.

## Features

- Develop a hardened image following STIGs.
- Ensure compliance with CIS benchmarks.
- Integrate automated patching and updates to maintain ongoing security.

## Prerequisites

Before using this project, ensure you have:

- An AWS account with IAM permissions.
- Cloudshell or AWS CLI installed and configured.
- Terraform or CloudFormation (optional, if used).

## Setup Instructions
Prepare the environment by:
- Launching an EC2 Instance (Amazon Linux 2).
- Obtain Linux 2 STIGs from the DoD Cyber Exchange and apply settings using build component (pipeline recipe).
- Apply the CIS benchmarks using CIS-CAT.
- Open Cloudshell and link your SSH to the instance using the command: SSH



## Install OpenSCAP on the EC2 Instance to scan and remediate configurations per STIGs guidelines



1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/aws-secure-golden-image.git
   cd aws-secure-golden-image
