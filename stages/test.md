# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Test  
### __Stage description:__  
This practical task consists of constructing a RACIVS matrix, this project management technique will be used to document and clearly outline the important steps that occur in a DevOps Testing team. The importance of the Testing team is to streamline the process which allows for continuous integration and deployment of program code.


| Pipeline Stage:<br>Test                   |   Developer  | Test Lead  | Client  |  Project Manager  | Tester  |Sys Admin  |
|------------------------------------------ |------------- |----------- |-------- |------------------ |-------- |---------- |
| Automate Unit Test Execution + Reporting  |      IC      |     S      |         |        C          |    V    |   RA      |
| Resolve Failed Tests                      |      R       |     AV     |         |        S          |    I    |           |
| Write SIT Test Plan / Scripts             |      C       |     AV     |         |        S          |    R    |           |
| Execute SIT                               |      I       |     AV     |         |        S          |    R    |           |
| Write UAT Test Plan / Scripts             |      A       |     VS     |    C    |        I          |    R    |           |
| Execute UAT                               |              |     S      |    R    |        I          |    AV   |           |
| Compile Test Completion Report            |      I       |     AV     |    S    |        S          |    R    |           |

**Assumption : Writing unit tests not included as would be done during dev phase in a TDD model.**

[Home](../index.md)  
