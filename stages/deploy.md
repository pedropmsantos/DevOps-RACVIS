# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Deploy  
### __Stage description:__  
The Deployment Stage

In the deployment stage, the code is deployed to the production servers. It must be verified that the code operates in the same way on the production server as in the development environment.
The new code is deployed continuously, and configuration management tools are used to execute tasks frequently.
Some popular tools used in this phase are, Chef, Puppet, Ansible, and SaltStack.

Containerization tools are used in the deployment phase. Vagrant and Docker are popular tools that are used for this purpose.
These tools help to produce consistency across development, staging, testing, and production environment. They can be used to softly scale up or down the load applied to the code base.

Containerization tools are used to maintain consistency across the environments where the application is tested, developed, and deployed.
When there is consistency across these environments, there is a reduced chance of bugs being introduced to the system when changing from development to deployment. This is due to the production environment having the same dependencies and packages as the development environment had.



| Pipeline Stage:<br>Deploy  | Client  | Product owner | Developer  | Tester  | System administrator |Security Team
|----------------------------- |-------- |-------- |-------- |--------  |--------  |---------
| Code compilation             |     I   |     I    |   A      |    S     |    I      |    I      |
| Code compliance             |      I   |     A, S    |   C      |    V     |    I      |    R      |
| Unit test                    |     I    |     A, S    |    V     |    R      |    C      |    I      |
| Code Analysis                |     I    |     S    |    R, A     |    C      |    I      |    I      |
| Perform Test Deployment      |    I     |     S    |     C    |     A     |     V     |     R     |             
| Perform Canary Deployment    |    V     |    A     |   C      |    I     |   R       |     C     |
| Perform Production Deployment |    I     |    S     |   A      |    V      |    R     |      V    |  
  
[Home](../index.md)  
