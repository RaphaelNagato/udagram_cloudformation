# CloudFormation Script for Udagram Infrastructure, A DevOps Project

A AWS CloudFromation script to create the infrastructure shown in this image ![Udagram Infrastructure](./Udagram%20Infrastructure.png)

This project is second of the four required projects needed to graduate from the [Udacity Cloud Devops Engineer Nanodegree Program](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991)

## Installation and Usage

Make sure git and AWS cli installed and configured on your system,open your terminal and change your path to your preferred directory then:

- Clone the repository with `git clone https://github.com/RaphaelNagato/udagram_cloudformation.git`
- Change directory using the command `cd udagram_cloudformation`
- Create the network using the command `./create.sh <stack-name> network.yml network-params.json`
- Then create the server respources using the command `./create.sh <another-stack-name> servers.yml servers-params.json`
- Now you can play with the infrastructure using the update.sh file using the command above but replacing the `./create.sh` with `./update.sh`
- Delete the infrastructure using the command `./delete.sh <stack name>`
- The Region is set to `us-east-1` by default, you can change it in all the `.sh` files

## Author

[Raphael Okeibunor](https://github.com/RaphaelNagato)
