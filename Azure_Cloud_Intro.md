1. Infrastructure as a service : Basic infrastructure like VM, Storage or Network Services
2. Platform as a service: Platforms which are already ready in the cloud for use like e.g
   Database platform where we can configure any database services like Mysql, MS-SQL or Postgresql.
3. Software as a service: Softwares that are directly available and we need not to do any configuration for it.
   We take the subscription OR use those software as pay-as-you-go. For e.g for email as a service we take outlook subscription.

=========================================

Resource, Resource Manager and Resource Group:

1. Resource: Any cloud resource we take into use or instance of the service is called
   as resource.
2. Resource Manager: User sends a request to resource manager to create a resource and
   as per the users request resource manager creates a resource and send it back to the user.
3. Resource group: It is a group of resources. We can define multiple resource groups for
   the different services. Every resource must have a resource group and it is always 1:1 mapping between resource and resource group. (i.e each resource only have one resource group)
   We can define resource group as per our project structure.
   for e.g payment_resource_group, transaction_resource_group etc
   It is really good way to manage resource groups in the Azure environment by assigning them Authrorization, Authentication,
   Security, Setting deployments etc.

We can create different Resource groups as per the organizations requirement or the
enviroment present in the organizations such as (QA group, Developers group or Production group)

Each environment would be handled by separate Microsoft Azure's account in the organization.

1. QA environment setup in the QA_Resource_Group have account name as : QA
   similarly for the Developers and Production they have their own cloud accounts
   to maintain the easyness among the different environemnts.
