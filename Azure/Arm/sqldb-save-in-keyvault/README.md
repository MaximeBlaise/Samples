# SQL Database with Key Vault

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMaximeBlaise%2FSamples%2Fmaster%2FAzure%2FArm%2Fsqldb-save-in-keyvault%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FMaximeBlaise%2FSamples%2Fmaster%2FAzure%2FArm%2Fsqldb-save-in-keyvault%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will deploy an instance of Azure SQL Database, and after store Connection String in a secure Key Vault, in order to transfer information to an other resource (for example an API App).

If you don't see secrets in key vault, it's maybe because you are not authorized to view them. But you can change access policies in a Key Vault easily in Azure Portal : just click on your keyvault resource and click on `Access policies` tab (on the left).

To learn more about resources used, please refer to Microsoft documentation : [Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/) or [Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/)
