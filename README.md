# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`
------------------------
To run a pipeline in azure devops we need agent. we can run our jobs on microsoft provided agents or selfhosted agent

1. steps to install of selfhosted agent:

Configure your account by following the steps outlined here.
	
* Create the agent 

~/$ mkdir myagent && cd myagent

* Download the agent: wget https://vstsagentpackage.azureedge.net/agent/2.194.0/vsts-agent-linux-x64-2.194.0.tar.gz

*untar the file

~/myagent$ tar zxvf vsts-agent-linux-x64-2.194.0.tar.gz

*Configure the agentDetailed instructions

~/myagent$ ./config.sh

~/myagent$ ./run.sh

That's it!
-----------------------
2.after all the setup, if we run our project we get parallelism error. 
  so, Request Free Parallelism for your organization: https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR63mUWPlq7NEsFZhkyH8jChUMlM3QzdDMFZOMkVBWU5BWFM3SDI2QlRBSC4u
  
------------------------------  

## please refer my loom video to deploy sample react application in azure devops

https://www.loom.com/share/f4dfb73c0678448f82ab6364e9953f19
https://www.loom.com/share/72622fa97a8b44af99d204a05c9b9525 
https://www.loom.com/share/f44ad3c2bffa4d8881aba3bdff9adbc5
