# ![LOGO](logo.png) PolicyEventsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the PolicyEventsClient API (version 2018-04-04).

Generated from: https://api.apis.guru/v2/specs/azure.com/policyinsights-policyEvents/2018-04-04/swagger.json<br/>
Generated at: 2019-05-07T17:38:35+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Queries policy events for the resources under the management group.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupName` - _required_ - Management group name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the resources under the subscription.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the subscription level policy assignment.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `authorizationNamespace` - _required_ - The namespace for Microsoft Authorization resource provider; only "Microsoft.Authorization" is allowed.
    Possible values: Microsoft.Authorization.
* `policyAssignmentName` - _required_ - Policy assignment name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the subscription level policy definition.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `authorizationNamespace` - _required_ - The namespace for Microsoft Authorization resource provider; only "Microsoft.Authorization" is allowed.
    Possible values: Microsoft.Authorization.
* `policyDefinitionName` - _required_ - Policy definition name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the subscription level policy set definition.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `authorizationNamespace` - _required_ - The namespace for Microsoft Authorization resource provider; only "Microsoft.Authorization" is allowed.
    Possible values: Microsoft.Authorization.
* `policySetDefinitionName` - _required_ - Policy set definition name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the resources under the resource group.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the resource group level policy assignment.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `authorizationNamespace` - _required_ - The namespace for Microsoft Authorization resource provider; only "Microsoft.Authorization" is allowed.
    Possible values: Microsoft.Authorization.
* `policyAssignmentName` - _required_ - Policy assignment name.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Queries policy events for the resource.

#### Input Parameters
* `policyEventsResource` - _required_ - The name of the virtual resource under PolicyEvents resource type; only "default" is allowed.
    Possible values: default.
* `resourceId` - _required_ - Resource ID.
* `api-version` - _required_ - API version to use with the client requests.
* `$top` - _optional_ - Maximum number of records to return.
* `$orderby` - _optional_ - Ordering expression using OData notation. One or more comma-separated column names with an optional "desc" (the default) or "asc", e.g. "$orderby=PolicyAssignmentId, ResourceId asc".
* `$select` - _optional_ - Select expression using OData notation. Limits the columns on each record to just those requested, e.g. "$select=PolicyAssignmentId, ResourceId".
* `$from` - _optional_ - ISO 8601 formatted timestamp specifying the start time of the interval to query. When not specified, the service uses ($to - 1-day).
* `$to` - _optional_ - ISO 8601 formatted timestamp specifying the end time of the interval to query. When not specified, the service uses request time.
* `$filter` - _optional_ - OData filter expression.
* `$apply` - _optional_ - OData apply expression for aggregations.

### Gets OData metadata XML document.

#### Input Parameters
* `scope` - _required_ - A valid scope, i.e. management group, subscription, resource group, or resource ID. Scope used has no effect on metadata returned.
* `api-version` - _required_ - API version to use with the client requests.

## License

**flow**ground :- Telekom iPaaS / azure-com-policyinsights-policy-events-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
