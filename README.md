# CosmosDB Emulator
This docker image is a [Comsos DB Emulator](https://learn.microsoft.com/it-it/azure/cosmos-db/local-emulator?tabs=ssl-netstd21) 
**without** the timer to avoid the following [issue](https://github.com/Azure/azure-cosmos-db-emulator-docker/issues/60).

The original image is:

`mcr.microsoft.com/cosmosdb/linux/azure-cosmos-emulator:latest`

# How To Use

`docker pull ghcr.io/pagopa/cosmosdb-emulator:sha-1f7028c`
