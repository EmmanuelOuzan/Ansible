# Ansible Emmanuel Repo
## This is my full ansible Directory.
### So what did I do?

1. You can find the zip + vim installation playbook in books directory :)
   I have made it the most efficient I could :) I updated it to the last ansible version
   (Loops updated to best practices)

2. I have created the "common" Role that can be found in the Roles directory.

3. I have wrote the server.yml that runs the "common" role inside its folder.

4. I have added an extra inventory file in the hosts folder + Used variables in the original
   hosts file

5. I have encrypted the private.pem file :) allowing me to make this repo public and stay secured :) 

6. I have added to the ansible configuration file the "Host key checking=false" So I wont have to write "yes" each time I connect to a server.

8. You can find the role that deploys "hello world" into the remote machines under the role
   "hello world"

9. Inside the books folder you can find the docker-ce install I work with to deploy docker
   
 
Emmanuel 
