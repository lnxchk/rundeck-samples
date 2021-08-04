Some things for linking Chef bits.

This demo allowed the *alice* user access to only run the chef-client job on the specified nodes.
I used the (Community Welcome Project)[https://docs.rundeck.com/docs/learning/tutorial/preparing.html] as the base for this, so there is a Rundeck server and some Ubuntu Linux nodes.

The *alice* user is also already configured.

Files:
* *Run_chef_client_on_demand.yaml* is the job definition for the "Run chef-client on demand" job in the Rundeck server.
* *AliceRunChefClient.yaml* is the ACL definition that allows the *alice* user to run the chef-client job.
