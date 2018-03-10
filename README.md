# Reference AWS CodePipeline with multiple sources

This is a reference AWS CodePipeline with multiple source repos. The purpose is to show how multiple teams can maintain artifacts/templates needed by the Pipeline.

 - I'm using 2 submodules with this reference AWS CodePipeline so it's easier to manage. Submodules are: submodule_AWS-Pipeline-API-GW-cfn-and-property-files & submodule_AWS-Pipeline-code
   - Submodule_AWS-Pipeline-API-GW-cfn-and-property-files - Will store our AWS API GW cfn along with a number of other AWS resources. It will also store both template configuration files.
   - Submodule_AWS-Pipeline-code - Will store our lambda code. Currently, it's just a 'helloworld' example.
   - 
 
