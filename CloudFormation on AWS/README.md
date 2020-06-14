			Deploy a high-availability application using CloudFormation.

Introduction
This is a project of Cloud DevOps Engineer Nanodegree Program on Udacity.


How to Build
To load network infrastructure code
./create.sh Udagram(Name) UdagramApp_network.yml UdagramApp_params.json


To load User Role (IAM) code
./create.sh UdagramApp-role(Name) UdagramApp_IAMRole.yml UdagramApp_IAMRoleparams.json


To load server infrastructure code
./create.sh UdagramApp-servers UdagramApp_server.yml UdagramApp_serverparams.json

Result
DNS: http://udagr-webap-1ny9a1uv79dyd-983167146.us-west-2.elb.amazonaws.com/


