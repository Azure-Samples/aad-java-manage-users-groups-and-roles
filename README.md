---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Authorization
  platforms: java
---

# Getting Started with Authorization - Manage Users Groups And Roles - in Java #


  Azure Users, Groups and Roles sample.
  - Create a user
  - Assign role to AD user
  - Revoke role from AD user
  - Get role by scope and role name
  - Create Service Principal
  - Assign role to Service Principal
  - Create 2 Active Directory groups
  - Add the user, the service principal and the 1st group as members of the 2nd group
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-java-manage-users-groups-and-roles.git

    cd aad-java-manage-users-groups-and-roles

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
