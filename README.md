There is a small sample project repo with 2 services we'd like you you to deploy here: https://github.com/RizeFinance/devops_test You can use any free or open source tools necessary to develop your solution, but the deployment environment must meet the following requirements:

*    We want to serve these services from a single server on port 1212 (sinatra) and 206 (webrick). The sinatra service should run on the puma web server, not the default webrick.

*    (Extra credit) on Tuesday & Thursday we want to serve webrick on port 1212 and sinatra on port 206

*    Changes to the git repo should trigger automated test/build/deploy

*    The services should be containerized

Please clone the repo and configure the environment as described. DO NOT submit a pull request against the origin repo. Instead, submit a link to your publicly available source code repository for review which provides the following:

*    One or more configuration files for the chosen containerization tool
*    An Ansible/Puppet/Saltstack/Chef/etc. script which provisions any needed resources on the target deployment server
* Any other configuration files required
*    A text document which contains:
  *    A description of each step of the CI/CD pipeline you would implement to ensure high availability
  *    Which EC2 instance type would be most appropriate for this deployment and why?
  *    List inbound rules you would add to the security group
  *    Explain why you chose this containerization tool. Compare and contrast it with at least one other containerization tool
