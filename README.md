# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2015-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-componentAnnotations_API/2015-05-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:17+03:00

## API Description

Azure Application Insights client for Annotations for a component.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the list of annotations for a component for given time range

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `start` - _required_ - The start time to query from for annotations, cannot be older than 90 days from current date.
* `end` - _required_ - The end time to query for annotations.

### Create an Annotation of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Delete an Annotation of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `annotationId` - _required_ - The unique annotation ID. This is unique within a Application Insights component.

### Get the annotation for given id.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `annotationId` - _required_ - The unique annotation ID. This is unique within a Application Insights component.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-component-annotations-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
