# Cloud-formation-web-app
This is a cloud formation project used to deploy a dummy application (a sample JavaScript or HTML file) to the Apache Web Server running on an EC2 instance.

## Description
Your company is creating an Instagram clone called Udagram.
Developers want to deploy a new application to the AWS infrastructure.
You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.
This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

## Cloud Formation Diagram
[]()

## Pre-requisites
### 1. AWS account
You would require to have an AWS account to access [AWS management console](https://aws.amazon.com/console/) to build cloud infrastructure.

### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](https://lucid.app/) is required to be able to draw the web app architecture diagrams for AWS.

## How it's built
- Diagram: A visual aid to understand the CloudFormation script. Made from [Lucidchart](www.lucidchart.com)
- Script: Interpret the diagram and create a matching CloudFormation script.

## Technologies Used
- [YAML](https://yaml.org/) - For the CloudFormation script.
- [JSON](https://www.json.org/json-en.html) - For the Parameters used by the CloudFormation script.

## How to run
```
- ./create.sh Udagram-servers Udagram-servers.yml Udagram-servers-params.json
- ./update.sh Udagram-servers Udagram-servers.yml Udagram-servers-params.json
```
Can be accessed in browser through this [link](http://Udagr-WebAp-SCS6ZOXMXVXK-1245339764.us-east-1.elb.amazonaws.com)




