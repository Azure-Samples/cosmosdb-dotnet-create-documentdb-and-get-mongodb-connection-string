---
page_type: sample
languages:
- csharp
products:
- azure
- azure-cosmos-db
extensions:
- services: Cosmos-DB
- platforms: dotnet
description: "Azure CosmosDB sample."
---

# Create a DocumentDB and get MongoDB connection string using C#

 Azure CosmosDB sample.
 
- Create a CosmosDB configured with MongoDB kind.
- Get the mongodb connection string
- Delete the CosmosDB.


## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/cosmosdb-dotnet-create-documentdb-and-get-mongodb-connection-string.git
cd cosmosdb-dotnet-create-documentdb-and-get-mongodb-connection-string
dotnet build
bin\Debug\net452\CreateCosmosDBWithKindMongoDB.exe
```

## More information

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
