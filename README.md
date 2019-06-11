# ![LOGO](logo.png) Azure Stack Azure Bridge Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Stack Azure Bridge Client API (version 2017-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azurestack-Registration/2017-06-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:45+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of all registrations.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `api-version` - _required_ - Client API Version.

### Delete the requested Azure Stack registration.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

### Returns the properties of an Azure Stack registration.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

### Patch an Azure Stack registration.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

### Create or update an Azure Stack registration.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

### Returns Azure Stack Activation Key.

*Tags:* `Registrations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azurestack-registration-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
