# ![LOGO](logo.png) Azure SQL Database disaster recovery configurations **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database disaster recovery configurations API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-disasterRecoveryConfigurations/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:03+03:00

## API Description

Provides create, read, update, delete, and failover functionality for Azure SQL Database disaster recovery configurations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a server's disaster recovery configuration.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Deletes a disaster recovery configuration.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `disasterRecoveryConfigurationName` - _required_ - The name of the disaster recovery configuration to be deleted.

### Gets a disaster recovery configuration.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `disasterRecoveryConfigurationName` - _required_ - The name of the disaster recovery configuration.

### Creates or updates a disaster recovery configuration.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `disasterRecoveryConfigurationName` - _required_ - The name of the disaster recovery configuration to be created/updated.

### Fails over from the current primary server to this server.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `disasterRecoveryConfigurationName` - _required_ - The name of the disaster recovery configuration to failover.

### Fails over from the current primary server to this server. This operation might result in data loss.

*Tags:* `DisasterRecoveryConfigurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `disasterRecoveryConfigurationName` - _required_ - The name of the disaster recovery configuration to failover forcefully.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-disaster-recovery-configurations-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
