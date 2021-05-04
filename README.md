Steps to perform to demo CICD showcase
Clone this particular branch into your local machine.
Create a Travis CI account with your Github account (https://travis-ci.com/signin)
travis login -u <github user> --org
Sync your repositories between Travis and Github: Goto https://travis-ci.com/account/repositories, hit "Sync Account", Activate all your repos.
Steps to do in you demo:
  *)Before trigeering a build you will need to configure the environment variables in your travis account i.e LEANIX_HOST AND LEANIX_TOKEN. The leanix host is the instance 
  in which the workspace is hosted and Leanix token is the api token. You will need to create these two variables in the environment variables section in travis and paste 
  the corresponding values.
  *)Trigger a build by making a change to the metadata.yml file.
  *)Check the status of your build in travis, once it is completed your data should be present in your workspace.
  
