# Azure-Function-Apps

Created code for copying files from one blob to another using Function app. 
And triggered it via a scheduler. Parameters also mentioned in the schedular.
Azure Functions is a serverless compute service that enables you to run code on-demand without having to explicitly provision or manage infrastructure. 
Azure Scheduler is an automatic action scheduler.
It defines the actions to run in the cloud and there by the scheduled actions are run automatically.
There are different approached the Azure schdulerr uses inorder to acived this, few common items are – Powershell, REST API.
The primary job of Azure Scheduler is to invoke the hosted code. This is done using HTTP calls or by a queue job using above mentioned approaches.
Every time a job is invoked, the scheduler will keep track of the executed job results for future review.
These actions as mentioned above are triggered by HTTP calls, Scheduler REST API plays key role in managing the action communication.
Typically Azure Scheduler is used in

   a. Applications that require or run on Data Feed / batch jobs.

   b. Application maintainance activities like - data backups or purging of logs has to do be done at a particular time when there is less traffic flow  for the application.
