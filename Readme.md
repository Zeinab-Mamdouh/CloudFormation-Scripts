This folder provides scripts for CloudFormation with steps. The folder contain some challenges I resolved from FWD schoolarShip:

### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor or Sublime text editor or ect as you like

But VS code editor would be helpful to visualize the image as well as code

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com] is required to be able to draw the web app architecture diagrams for AWS.
#####################################################
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh Challenge2Project Challenge2.yml Challenge2-params.json
# For updates
./update.sh Challenge2Project Challenge2.yml Challenge2-params.json 
