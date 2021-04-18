# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Code  
### __Stage description:__  
The Coding stage

In this stage, developers start coding. Developers usually have to follow certain coding styles to ensure consistency through out the application.
This makes understanding the code by any team member much easier. When code is ready, developers make a pull request to the shared source code repository. 
Team members can review the submitted code and merge it with the master branch by approving the initial pull request.


| Pipeline Stage:<br>Code  | Client  | Product owner  | Developer | Tester  |   UX    | System administrator |
|------------------------- |-------- |--------------- |---------- |-------- |-------- | -------------------- |
| Implementing features    |         |      AV        |     R     |    CI   |    C    |                      |
| Writing documentation    |    CI   |      AV        |     RCV   |    R    |         | RCV                  |
| Refactoring code         |         |                |     RA    |    R    |    I    |                      |
| Performance testing      |         |                |     C     |    RA   |         |  CV                  |
| Code review              |         |                |     RVA   |    I    |    I    |                      |
| Product release          |    I    |     AVIS       |     ARS   |    S    |    CV   |  VI                  |
  
[Home](../index.md)  
