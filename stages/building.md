# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Build  
### __Stage description:__ 
Building a software project involves taking source code and compiling it for execution and release. For example, compiling Java source code into byte code.
In a DevOps Pipeline, the build process ensures seemless integration of code submitted by different developers. Builds can be scheduled, triggered manually or a repository can be configured to automatically build a project upon commits and merges. This process ensures that each developer is using appropriate libraries and dependencies. If a build fails, the developer will be notified and they will need to make the necessary changes to their code before merging their branch with the main branch.
Tools such as Maven and Gradle are used to build the project in the same way that we use these tools to build projects on our local machines. The difference with a DevOps Pipeline is that the versions, libraries and depenedencies are defined in the repository's actions so each developer is singing off the same hymn sheet, so to speak.

There are a number of decisions to be made when designing the build process:
  - What tools to use
  - When to build
  - What platform to build for
  - What files to build

Some of the roles involved in a DevOps build process may include:
  - Developers
  - Product Owner
  - Client
  - Designer
  - QA
  - Automation Architect
  - Security Engineer


Responsible   Accountable  Consulted    Verifier    Informed    Signatory


| Pipeline Stage:<br>Build  | Developers | Product Owner| Client       | Designer     | QA          |Auto. Arch.   |Security Eng|
|----------------------------- |------------- |------------- |------------- |------------- |------------- |------------ |------------ |
| Choosing tools               | I            | R            |              | C            | C            | RA          | CV
| Deciding when to build       | I            | R            |              | I            |              | RA          | 
| What platform to build for   | I            | I A          | C            | I            |              | I           | 
| What files to build          | I            | R            |              | I            |              | RA          |   
  
[Home](../index.md)  
