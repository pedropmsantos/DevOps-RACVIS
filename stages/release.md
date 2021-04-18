# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Release  
### __Stage description:__  

The release stage is between the **Test** and **Deploy** stages, here is where we can implement the CI/CD in our pipeline, but first it needs to how we are going to test and deploy the code, in this case we have decided the release will have three stages:

* **Release to QA**: Here is where the code will be released to QA environment, so it can be properly tested (manually or automated tests) by both developers and QA Engineers, assuming there is no issues/bugs found, the code will then be released to Staging environment.

* **Release to Staging (if no issues in QA)**: The code will be related to Staging environment and all automated testes will be triggered, assuming the code changes didn't break tests, the release will proceed to the next stage.

* **Release to Production (if no issues in Staging)**: At this point the code has been properly tested and should not cause any unexpected issues in production, therefore it should be safe to deploy to production.

In case an issue is reported in one of those stages, a rollback strategy will need to be done, so it doesn't cause issues to any user, a simple strategy is to revert the latests code changes and do a new release with the fix later.


| Pipeline Stage:<br>Release  | Product Owner  | Client  | Developer  | Senior Manager  | QA Engineer  |
|----------------------------- |-------- |-------- |-------- |-------- |-------- |
| Release to QA                |    I     |        |   RA     |         |    RV     |
| Release to Staging if tests pass    |    I     |         |   RA     |    I     |    VA    |
| Release to Production if tests pass       |    SA     |    I     |   R     |    C     |    V    |
  
  
[Home](../index.md)  
