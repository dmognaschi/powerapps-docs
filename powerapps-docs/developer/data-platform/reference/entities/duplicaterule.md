---
title: "Duplicate Detection Rule (DuplicateRule) table/entity reference (Microsoft Dataverse)"
description: "Includes schema information and supported messages for the Duplicate Detection Rule (DuplicateRule) table/entity with Microsoft Dataverse."
ms.date: 01/06/2025
ms.service: powerapps
ms.topic: reference
author: phecke
ms.author: pehecke
search.audienceType: 
  - developer
---

# Duplicate Detection Rule (DuplicateRule) table/entity reference

Rule used to identify potential duplicates.

## Messages

The following table lists the messages for the Duplicate Detection Rule (DuplicateRule) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: False |`PATCH` /duplicaterules(*duplicateruleid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `CompoundCreate`<br />Event: False | |<xref:Microsoft.Crm.Sdk.Messages.CompoundCreateRequest>|
| `CompoundUpdateDuplicateDetectionRule`<br />Event: False |<xref:Microsoft.Dynamics.CRM.CompoundUpdateDuplicateDetectionRule?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.CompoundUpdateDuplicateDetectionRuleRequest>|
| `Create`<br />Event: False |`POST` /duplicaterules<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `Delete`<br />Event: False |`DELETE` /duplicaterules(*duplicateruleid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: False |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `ModifyAccess`<br />Event: False |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `PublishDuplicateRule`<br />Event: False |<xref:Microsoft.Dynamics.CRM.PublishDuplicateRule?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.PublishDuplicateRuleRequest>|
| `PublishXml`<br />Event: False |<xref:Microsoft.Dynamics.CRM.PublishXml?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.PublishXmlRequest>|
| `Retrieve`<br />Event: False |`GET` /duplicaterules(*duplicateruleid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: False |`GET` /duplicaterules<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: False |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: False |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: False |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `UnpublishDuplicateRule`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UnpublishDuplicateRule?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.UnpublishDuplicateRuleRequest>|
| `Update`<br />Event: False |`PATCH` /duplicaterules(*duplicateruleid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `Upsert`<br />Event: False |`PATCH` /duplicaterules(*duplicateruleid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|

## Properties

The following table lists selected properties for the Duplicate Detection Rule (DuplicateRule) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Duplicate Detection Rule** |
| **DisplayCollectionName** | **Duplicate Detection Rules** |
| **SchemaName** | `DuplicateRule` |
| **CollectionSchemaName** | `DuplicateRules` |
| **EntitySetName** | `duplicaterules`|
| **LogicalName** | `duplicaterule` |
| **LogicalCollectionName** | `duplicaterules` |
| **PrimaryIdAttribute** | `duplicateruleid` |
| **PrimaryNameAttribute** |`name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [BaseEntityName](#BKMK_BaseEntityName)
- [Description](#BKMK_Description)
- [DuplicateRuleId](#BKMK_DuplicateRuleId)
- [ExcludeInactiveRecords](#BKMK_ExcludeInactiveRecords)
- [IsCaseSensitive](#BKMK_IsCaseSensitive)
- [IsCustomizable](#BKMK_IsCustomizable)
- [MatchingEntityName](#BKMK_MatchingEntityName)
- [Name](#BKMK_Name)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [StatusCode](#BKMK_StatusCode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UniqueName](#BKMK_UniqueName)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_BaseEntityName"></a> BaseEntityName

|Property|Value|
|---|---|
|Description|**Record type of the record being evaluated for potential duplicates.**|
|DisplayName|**Base Record Type**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`baseentityname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|160|

### <a name="BKMK_Description"></a> Description

|Property|Value|
|---|---|
|Description|**Description of the duplicate detection rule.**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`description`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_DuplicateRuleId"></a> DuplicateRuleId

|Property|Value|
|---|---|
|Description|**Unique identifier of the duplicate detection rule.**|
|DisplayName|**Duplicate Detection Rule**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`duplicateruleid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_ExcludeInactiveRecords"></a> ExcludeInactiveRecords

|Property|Value|
|---|---|
|Description|**Determines whether to flag inactive records as duplicates**|
|DisplayName|**Exclude Inactive Records**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`excludeinactiverecords`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`duplicaterule_excludeinactiverecords`|
|DefaultValue|False|
|True Label|True|
|False Label|False|

### <a name="BKMK_IsCaseSensitive"></a> IsCaseSensitive

|Property|Value|
|---|---|
|Description|**Indicates if the operator is case-sensitive.**|
|DisplayName|**Case Sensitive**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`iscasesensitive`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`duplicaterule_iscasesensitive`|
|DefaultValue|False|
|True Label|True|
|False Label|False|

### <a name="BKMK_IsCustomizable"></a> IsCustomizable

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Is Customizable**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`iscustomizable`|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|

### <a name="BKMK_MatchingEntityName"></a> MatchingEntityName

|Property|Value|
|---|---|
|Description|**Record type of the records being evaluated as potential duplicates.**|
|DisplayName|**Matching Record Type**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`matchingentityname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|160|

### <a name="BKMK_Name"></a> Name

|Property|Value|
|---|---|
|Description|**Name of the duplicate detection rule.**|
|DisplayName|**Rule Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`name`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|160|

### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|---|---|
|Description|**Unique identifier of the user or team who owns the duplicate detection rule.**|
|DisplayName|**Owner**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ownerid`|
|RequiredLevel|SystemRequired|
|Type|Owner|
|Targets|systemuser, team|

### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridtype`|
|RequiredLevel|SystemRequired|
|Type|EntityName|

### <a name="BKMK_StatusCode"></a> StatusCode

|Property|Value|
|---|---|
|Description|**Reason for the status of the duplicate detection rule.**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|SystemRequired|
|Type|Status|
|DefaultFormValue|-1|
|GlobalChoiceName|`duplicaterule_statuscode`|

#### StatusCode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Unpublished**<br />State:0<br />TransitionData: None|
|1|Label: **Publishing**<br />State:0<br />TransitionData: None|
|2|Label: **Published**<br />State:1<br />TransitionData: None|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_UniqueName"></a> UniqueName

|Property|Value|
|---|---|
|Description||
|DisplayName|**UniqueName**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`uniquename`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [BaseEntityMatchCodeTable](#BKMK_BaseEntityMatchCodeTable)
- [BaseEntityTypeCode](#BKMK_BaseEntityTypeCode)
- [ComponentIdUnique](#BKMK_ComponentIdUnique)
- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [IsManaged](#BKMK_IsManaged)
- [MatchingEntityMatchCodeTable](#BKMK_MatchingEntityMatchCodeTable)
- [MatchingEntityTypeCode](#BKMK_MatchingEntityTypeCode)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OverwriteTime](#BKMK_OverwriteTime)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [SolutionId](#BKMK_SolutionId)
- [StateCode](#BKMK_StateCode)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)

### <a name="BKMK_BaseEntityMatchCodeTable"></a> BaseEntityMatchCodeTable

|Property|Value|
|---|---|
|Description|**Database table that stores match codes for the record type being evaluated for potential duplicates.**|
|DisplayName|**Base Record Type Match Code Table**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`baseentitymatchcodetable`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|50|

### <a name="BKMK_BaseEntityTypeCode"></a> BaseEntityTypeCode

|Property|Value|
|---|---|
|Description|**Record type of the record being evaluated for potential duplicates.**|
|DisplayName|**Base Record Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`baseentitytypecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`duplicaterule_baseentitytypecode`|

#### BaseEntityTypeCode Choices/Options

|Value|Label|
|---|---|
|1|**Account**|
|2|**Contact**|
|5|**Note**|
|6|**Business Unit Map**|
|7|**Owner**|
|8|**User**|
|9|**Team**|
|10|**Business Unit**|
|14|**System User Principal**|
|29|**Subscription**|
|30|**Filter Template**|
|31|**Privilege Object Type Code**|
|33|**Subscription Synchronization Information**|
|35|**Tracking information for deleted entities**|
|36|**Client update**|
|37|**Subscription Manually Tracked Object**|
|42|**SystemUser BusinessUnit Entity Map**|
|44|**Field Sharing**|
|45|**Subscription Statistic Offline**|
|46|**Subscription Statistic Outlook**|
|47|**Subscription Sync Entry Offline**|
|48|**Subscription Sync Entry Outlook**|
|50|**Position**|
|51|**System User Manager Map**|
|52|**User Search Facet**|
|54|**Global Search Configuration**|
|55|**FileAttachment**|
|60|**SystemUserAuthorizationChangeTracker**|
|61|**PrincipalEntityBusinessUnitMap**|
|72|**Record Filter**|
|73|**EntityRecordFilter**|
|74|**Secured Masking Rule**|
|75|**Privilege Checker Run**|
|76|**Privilege Checker Log**|
|78|**Virtual Entity Data Provider**|
|85|**Virtual Entity Data Source**|
|92|**Team template**|
|99|**Social Profile**|
|101|**Service Plan**|
|103|**Privileges Removal Setting**|
|126|**Indexed Article**|
|127|**Article**|
|129|**Subject**|
|132|**Announcement**|
|135|**Activity Party**|
|150|**User Settings**|
|300|**Canvas App**|
|301|**Callback Registration**|
|372|**Connector**|
|373|**Connection Instance**|
|380|**Environment Variable Definition**|
|381|**Environment Variable Value**|
|400|**AI Template**|
|401|**AI Model**|
|402|**AI Configuration**|
|418|**Dataflow**|
|430|**Entity Analytics Config**|
|431|**Image Attribute Configuration**|
|432|**Entity Image Configuration**|
|950|**New Process**|
|951|**Translation Process**|
|955|**Expired Process**|
|1001|**Attachment**|
|1002|**Attachment**|
|1003|**Internal Address**|
|1007|**Image Descriptor**|
|1016|**Article Template**|
|1019|**Organization**|
|1021|**Organization UI**|
|1023|**Privilege**|
|1030|**System Form**|
|1031|**User Dashboard**|
|1036|**Security Role**|
|1037|**Role Template**|
|1039|**View**|
|1043|**String Map**|
|1071|**Address**|
|1072|**Subscription Clients**|
|1075|**Status Map**|
|1082|**Article Comment**|
|1086|**User Fiscal Calendar**|
|1094|**Authorization Server**|
|1095|**Partner Application**|
|1111|**System Chart**|
|1112|**User Chart**|
|1113|**Ribbon Tab To Command Mapping**|
|1115|**Ribbon Context Group**|
|1116|**Ribbon Command**|
|1117|**Ribbon Rule**|
|1120|**Application Ribbons**|
|1130|**Ribbon Difference**|
|1140|**Replication Backlog**|
|1189|**Document Suggestions**|
|1190|**SuggestionCardTemplate**|
|1200|**Field Security Profile**|
|1201|**Field Permission**|
|1203|**Team Profiles**|
|1204|**Application**|
|1234|**Channel Property Group**|
|1236|**Channel Property**|
|1300|**SocialInsightsConfiguration**|
|1309|**Saved Organization Insights Configuration**|
|1400|**Sync Attribute Mapping Profile**|
|1401|**Sync Attribute Mapping**|
|1403|**Team Sync-Attribute Mapping Profiles**|
|1404|**Principal Sync Attribute Map**|
|2000|**Annual Fiscal Calendar**|
|2001|**Semiannual Fiscal Calendar**|
|2002|**Quarterly Fiscal Calendar**|
|2003|**Monthly Fiscal Calendar**|
|2004|**Fixed Monthly Fiscal Calendar**|
|2010|**Email Template**|
|2012|**Unresolved Address**|
|2013|**Territory**|
|2015|**Theme**|
|2016|**User Mapping**|
|2020|**Queue**|
|2023|**QueueItemCount**|
|2024|**QueueMemberCount**|
|2027|**License**|
|2029|**Queue Item**|
|2500|**User Entity UI Settings**|
|2501|**User Entity Instance Data**|
|3000|**Integration Status**|
|3005|**Channel Access Profile**|
|3008|**External Party**|
|3231|**Connection Role**|
|3233|**Connection Role Object Type Code**|
|3234|**Connection**|
|4003|**Calendar**|
|4004|**Calendar Rule**|
|4011|**Inter Process Lock**|
|4023|**Email Hash**|
|4101|**Display String Map**|
|4102|**Display String**|
|4110|**Notification**|
|4120|**Exchange Sync Id Mapping**|
|4200|**Activity**|
|4201|**Appointment**|
|4202|**Email**|
|4204|**Fax**|
|4207|**Letter**|
|4210|**Phone Call**|
|4212|**Task**|
|4216|**Social Activity**|
|4220|**UntrackedEmail**|
|4230|**Saved View**|
|4231|**Metadata Difference**|
|4232|**Business Data Localized Label**|
|4250|**Recurrence Rule**|
|4251|**Recurring Appointment**|
|4299|**Email Search**|
|4410|**Data Import**|
|4411|**Data Map**|
|4412|**Import Source File**|
|4413|**Import Data**|
|4414|**Duplicate Detection Rule**|
|4415|**Duplicate Record**|
|4416|**Duplicate Rule Condition**|
|4417|**Column Mapping**|
|4418|**List Value Mapping**|
|4419|**Lookup Mapping**|
|4420|**Owner Mapping**|
|4423|**Import Log**|
|4424|**Bulk Delete Operation**|
|4425|**Bulk Delete Failure**|
|4426|**Transformation Mapping**|
|4427|**Transformation Parameter Mapping**|
|4428|**Import Entity Mapping**|
|4450|**Data Performance Dashboard**|
|4490|**Office Document**|
|4500|**Relationship Role**|
|4501|**Relationship Role Map**|
|4502|**Customer Relationship**|
|4567|**Auditing**|
|4579|**Ribbon Client Metadata.**|
|4600|**Entity Map**|
|4601|**Attribute Map**|
|4602|**Plug-in Type**|
|4603|**Plug-in Type Statistic**|
|4605|**Plug-in Assembly**|
|4606|**Sdk Message**|
|4607|**Sdk Message Filter**|
|4608|**Sdk Message Processing Step**|
|4609|**Sdk Message Request**|
|4610|**Sdk Message Response**|
|4611|**Sdk Message Response Field**|
|4613|**Sdk Message Pair**|
|4614|**Sdk Message Request Field**|
|4615|**Sdk Message Processing Step Image**|
|4616|**Sdk Message Processing Step Secure Configuration**|
|4618|**Service Endpoint**|
|4619|**Plug-in Trace Log**|
|4700|**System Job**|
|4702|**Workflow Wait Subscription**|
|4703|**Process**|
|4704|**Process Dependency**|
|4705|**ISV Config**|
|4706|**Process Log**|
|4707|**Application File**|
|4708|**Organization Statistic**|
|4709|**Site Map**|
|4710|**Process Session**|
|4711|**Expander Event**|
|4712|**Process Trigger**|
|4720|**Flow Session**|
|4724|**Process Stage**|
|4725|**Business Process Flow Instance**|
|4800|**Web Wizard**|
|4802|**Wizard Page**|
|4803|**Web Wizard Access Privilege**|
|4810|**Time Zone Definition**|
|4811|**Time Zone Rule**|
|4812|**Time Zone Localized Name**|
|5000|**Recently Used**|
|5004|**NL2SQ Registration Information**|
|7000|**System Application Metadata**|
|7001|**User Application Metadata**|
|7100|**Solution**|
|7101|**Publisher**|
|7102|**Publisher Address**|
|7103|**Solution Component**|
|7104|**Solution Component Definition**|
|7105|**Dependency**|
|7106|**Dependency Node**|
|7107|**Invalid Dependency**|
|7108|**Dependency Feature**|
|7200|**RuntimeDependency**|
|7755|**ElasticFileAttachment**|
|8000|**Post**|
|8001|**Post Role**|
|8002|**Post Regarding**|
|8003|**Follow**|
|8005|**Comment**|
|8006|**Like**|
|8040|**ACIViewMapper**|
|8050|**Trace**|
|8051|**Trace Association**|
|8052|**Trace Regarding**|
|8181|**Routing Rule Set**|
|8199|**Rule Item**|
|8700|**AppModule Metadata**|
|8701|**AppModule Metadata Dependency**|
|8702|**AppModule Metadata Async Operation**|
|8840|**Hierarchy Rule**|
|9006|**Model-driven App**|
|9007|**App Module Component**|
|9009|**App Module Roles**|
|9011|**App Config Master**|
|9012|**App Configuration**|
|9013|**App Configuration Instance**|
|9100|**Report**|
|9101|**Report Related Entity**|
|9102|**Report Related Category**|
|9103|**Report Visibility**|
|9104|**Report Link**|
|9105|**Currency**|
|9106|**Mail Merge Template**|
|9107|**Import Job**|
|9201|**LocalConfigStore**|
|9300|**Record Creation and Update Rule**|
|9301|**Record Creation and Update Rule Item**|
|9333|**Web Resource**|
|9400|**Channel Access Profile Rule**|
|9401|**Channel Access Profile Rule Item**|
|9502|**SharePoint Site**|
|9507|**Sharepoint Document**|
|9508|**Document Location**|
|9509|**SharePoint Data**|
|9510|**Rollup Properties**|
|9511|**Rollup Job**|
|9600|**Goal**|
|9602|**Rollup Query**|
|9603|**Goal Metric**|
|9604|**Rollup Field**|
|9605|**Email Server Profile**|
|9606|**Mailbox**|
|9607|**Mailbox Statistics**|
|9608|**Mailbox Auto Tracking Folder**|
|9609|**Mailbox Tracking Category**|
|9650|**Process Configuration**|
|9690|**Organization Insights Notification**|
|9699|**Organization Insights Metric**|
|9750|**SLA**|
|9751|**SLA Item**|
|9752|**SLA KPI Instance**|
|9753|**Custom Control**|
|9754|**Custom Control Resource**|
|9755|**Custom Control Default Config**|
|9800|**Entity**|
|9808|**Attribute**|
|9809|**OptionSet**|
|9810|**Entity Key**|
|9811|**Entity Relationship**|
|9812|**Managed Property**|
|9813|**Relationship Entity**|
|9814|**Relationship Attribute**|
|9815|**Entity Index**|
|9816|**Index Attribute**|
|9820|**Secured Masking Column**|
|9866|**Mobile Offline Profile**|
|9867|**Mobile Offline Profile Item**|
|9868|**Mobile Offline Profile Item Association**|
|9869|**Sync Error**|
|9870|**Offline Command Definition**|
|9875|**Language Provisioning State**|
|9880|**Ribbon Metadata To Process**|
|9890|**SolutionHistoryData**|
|9900|**Navigation Setting**|
|9910|**MultiEntitySearch**|
|9912|**Multi Select Option Value**|
|9919|**Hierarchy Security Configuration**|
|9930|**Knowledge Base Record**|
|9932|**Time Stamp Date Mapping**|
|9936|**Azure Service Connection**|
|9940|**Document Template**|
|9941|**Personal Document Template**|
|9945|**Text Analytics Entity Mapping**|
|9947|**Knowledge Search Model**|
|9949|**Advanced Similarity Rule**|
|9950|**Office Graph Document**|
|9951|**Similarity Rule**|
|9953|**Knowledge Article**|
|9955|**Knowledge Article Views**|
|9957|**Language**|
|9958|**Feedback**|
|9959|**Category**|
|9960|**Knowledge Article Category**|
|9961|**DelveActionHub**|
|9962|**Action Card**|
|9968|**ActionCardUserState**|
|9973|**Action Card User Settings**|
|9983|**Action Card Type**|
|9986|**Interaction for Email**|
|9987|**External Party Item**|
|9996|**HolidayWrapper**|
|9997|**Email Signature**|
|10000|**Solution Component Attribute Configuration**|
|10001|**Solution Component Batch Configuration**|
|10002|**Solution Component Configuration**|
|10003|**Solution Component Relationship Configuration**|
|10004|**Solution History**|
|10005|**Solution History Data Source**|
|10006|**Component Layer**|
|10007|**Component Layer Data Source**|
|10008|**Package**|
|10009|**Package History**|
|10011|**StageSolutionUpload**|
|10012|**ExportSolutionUpload**|
|10013|**FeatureControlSetting**|
|10014|**Solution Component Summary**|
|10015|**Solution Component Count Summary**|
|10016|**Solution Component Data Source**|
|10017|**Solution Component Count Data Source**|
|10018|**Microsoft Entra ID**|
|10019|**Staged Entity**|
|10020|**Staged Entity Attribute**|
|10021|**Staged Metadata Async Operation**|
|10022|**Key Vault Reference**|
|10023|**Managed Identity**|
|10024|**Catalog**|
|10025|**Catalog Assignment**|
|10026|**Internal Catalog Assignment**|
|10027|**Custom API**|
|10028|**Custom API Request Parameter**|
|10029|**Custom API Response Property**|
|10030|**Plugin Package**|
|10031|**NonRelational Data Source**|
|10032|**ProvisionLanguageForUser**|
|10033|**Shared Object**|
|10034|**Shared Workspace**|
|10035|**Shared Workspace Access Token**|
|10036|**Shared Workspace Pool**|
|10037|**Data Lake Folder**|
|10038|**Data Lake Folder Permission**|
|10039|**Data Lake Workspace**|
|10040|**Data Lake Workspace Permission**|
|10041|**Data Processing configuration**|
|10042|**Exported Excel**|
|10043|**RetainedData Excel**|
|10044|**Synapse Database**|
|10045|**Synapse Link External Table State**|
|10046|**Synapse Link Profile**|
|10047|**Synapse Link Profile Entity**|
|10048|**Synapse Link Profile Entity State**|
|10049|**Synapse Link Schedule**|
|10050|**Component Version**|
|10051|**Component Version Data Source**|
|10052|**Component Version (Internal)**|
|10053|**Git Branch**|
|10054|**Git Configuration Retrieval Data Source**|
|10055|**Git Organization**|
|10056|**Git Project**|
|10057|**Git Repository**|
|10058|**Source Control Branch Configuration**|
|10059|**Source Control Component**|
|10060|**Source Control Component Payload**|
|10061|**Source Control Configuration**|
|10062|**DataflowRefreshHistory**|
|10063|**EntityRefreshHistory**|
|10064|**Shared Link Setting**|
|10065|**DelegatedAuthorization**|
|10067|**CascadeGrantRevokeAccessRecordsTracker**|
|10068|**CascadeGrantRevokeAccessVersionTracker**|
|10069|**RevokeInheritedAccessRecordsTracker**|
|10070|**TdsMetadata**|
|10071|**Model-Driven App Element**|
|10072|**Model-Driven App Component Node's Edge**|
|10073|**Model-Driven App Component Node**|
|10074|**Model-Driven App Setting**|
|10075|**Model-Driven App User Setting**|
|10076|**Organization Setting**|
|10077|**Setting Definition**|
|10078|**CanvasApp Extended Metadata**|
|10079|**Service Plan Mapping**|
|10080|**Service Plan Custom Control**|
|10082|**ApplicationUser**|
|10085|**OData v4 Data Source**|
|10086|**Workflow Binary**|
|10087|**Credential**|
|10088|**Desktop Flow Module**|
|10089|**Flow Capacity Assignment**|
|10090|**Flow Credential Application**|
|10091|**Flow Event**|
|10092|**Flow Machine**|
|10093|**Flow Machine Group**|
|10094|**Flow Machine Image**|
|10095|**Flow Machine Image Version**|
|10096|**Flow Machine Network**|
|10097|**ProcessStageParameter**|
|10098|**Work Queue**|
|10099|**Work Queue Item**|
|10100|**Desktop Flow Binary**|
|10101|**Flow Log**|
|10102|**Flow Run**|
|10103|**Action Approval Model**|
|10104|**Approval**|
|10105|**Approval Request**|
|10106|**Approval Response**|
|10107|**Approval Step**|
|10108|**Await All Action Approval Model**|
|10109|**Await All Approval Model**|
|10110|**Basic Approval Model Data**|
|10111|**Flow Approval**|
|10120|**Connection Reference**|
|10121|**DVFileSearch**|
|10122|**DVFileSearchAttribute**|
|10123|**DVFileSearchEntity**|
|10124|**DVTableSearch**|
|10125|**DVTableSearchAttribute**|
|10126|**DVTableSearchEntity**|
|10127|**AICopilot**|
|10128|**AIPluginAuth**|
|10129|**AI Plugin Conversation Starter**|
|10130|**AI Plugin Conversation Starter Mapping**|
|10131|**AI Plugin Governance**|
|10132|**AI Plugin Governance Extended**|
|10133|**AIPluginOperationResponseTemplate**|
|10134|**AIPluginTitle**|
|10135|**SideloadedAIPlugin**|
|10136|**AIPlugin**|
|10137|**AIPluginExternalSchema**|
|10138|**AIPluginExternalSchemaProperty**|
|10139|**AIPluginInstance**|
|10140|**AIPluginOperation**|
|10141|**AIPluginOperationParameter**|
|10142|**AIPluginUserSetting**|
|10144|**AI Event**|
|10145|**AI Builder Feedback Loop**|
|10146|**AI Form Processing Document**|
|10147|**AI Object Detection Image**|
|10148|**AI Object Detection Label**|
|10149|**AI Object Detection Bounding Box**|
|10150|**AI Object Detection Image Mapping**|
|10152|**AI Builder Dataset**|
|10153|**AI Builder Dataset File**|
|10154|**AI Builder Dataset Record**|
|10155|**AI Builder Datasets Container**|
|10156|**AI Builder File**|
|10157|**AI Builder File Attached Data**|
|10158|**Help Page**|
|10159|**Tour**|
|10160|**BotContent**|
|10161|**ConversationTranscript**|
|10162|**Copilot**|
|10163|**Copilot component**|
|10164|**Copilot component collection**|
|10175|**Comment**|
|10176|**Governance Configuration**|
|10177|**Fabric AISkill**|
|10178|**App Insights Metadata**|
|10179|**Dataflow Connection Reference**|
|10180|**Schedule**|
|10181|**Dataflow Template**|
|10182|**Dataflow DatalakeFolder**|
|10183|**Data Movement Service Request**|
|10184|**Data Movement Service Request Status**|
|10185|**DMS Sync Request**|
|10186|**DMS Sync Status**|
|10187|**Knowledge Asset Configuration**|
|10188|**Module Run Detail**|
|10189|**QnA**|
|10190|**Salesforce Structured Object**|
|10191|**Salesforce Structured QnA Config**|
|10192|**Workflow Action Status**|
|10193|**FederatedKnowledgeConfiguration**|
|10194|**FederatedKnowledgeEntityConfiguration**|
|10195|**Form Mapping**|
|10196|**PDF Setting**|
|10197|**Activity File Attachment**|
|10198|**Teams chat**|
|10199|**Service Configuration**|
|10200|**SLA KPI**|
|10201|**Integrated search provider**|
|10202|**Knowledge Management Setting**|
|10203|**Knowledge Federated Article**|
|10204|**Knowledge Federated Article Incident**|
|10205|**Search provider**|
|10206|**Knowledge Article Image**|
|10207|**Knowledge Configuration**|
|10208|**Knowledge Interaction Insight**|
|10209|**Knowledge Search Insight**|
|10210|**Favorite knowledge article**|
|10211|**Knowledge article language setting**|
|10212|**Knowledge Article Attachment**|
|10213|**Knowledge personalization**|
|10214|**Knowledge Article Template**|
|10215|**Knowledge search personal filter config**|
|10216|**Knowledge search filter**|
|10218|**msdyn_historicalcaseharvestbatch**|
|10219|**msdyn_historicalcaseharvestrun**|
|10220|**Knowledge Harvest Job Record**|
|10221|**SupportUserTable**|
|10222|**FxExpression**|
|10223|**Function**|
|10224|**Plug-in**|
|10225|**PowerfxRule**|
|10226|**Planner Business Scenario**|
|10227|**Planner Sync Action**|
|10228|**Ms Graph Resource To Subscription**|
|10229|**Virtual Entity  Metadata**|
|10230|**Background Operation**|
|10231|**Report Parameter**|
|10232|**MobileOfflineProfileExtension**|
|10233|**MobileOfflineProfileItemFilter**|
|10234|**TeamMobileOfflineProfileMembership**|
|10235|**UserMobileOfflineProfileMembership**|
|10236|**OrganizationDataSyncSubscription**|
|10237|**OrganizationDataSyncSubscriptionEntity**|
|10238|**OrganizationDataSyncSubscriptionFnoTable**|
|10239|**OrganizationDataSyncFnoState**|
|10240|**OrganizationDataSyncState**|
|10241|**ArchiveCleanupInfo**|
|10242|**ArchiveCleanupOperation**|
|10243|**BulkArchiveConfig**|
|10244|**BulkArchiveFailureDetail**|
|10245|**BulkArchiveOperation**|
|10246|**BulkArchiveOperationDetail**|
|10247|**EnableArchivalRequest**|
|10248|**MetadataForArchival**|
|10249|**ReconciliationEntityInfo**|
|10250|**ReconciliationEntityStepInfo**|
|10251|**ReconciliationInfo**|
|10252|**RetentionCleanupInfo**|
|10253|**RetentionCleanupOperation**|
|10254|**RetentionConfig**|
|10255|**RetentionFailureDetail**|
|10256|**RetentionOperation**|
|10257|**RetentionOperationDetail**|
|10258|**RetentionSuccessDetail**|
|10259|**CertificateCredential**|
|10260|**Notification**|
|10261|**User Rating**|
|10262|**Mobile App**|
|10263|**Insights Store Data Source**|
|10264|**Insights Store Virtual Entity**|
|10265|**RoleEditorLayout**|
|10266|**Deleted Record Reference**|
|10267|**Restore Deleted Records Configuration**|
|10268|**App Action**|
|10269|**App Action Migration**|
|10270|**App Action Rule**|
|10273|**Card**|
|10274|**Card State Item**|
|10277|**Entity link chat configuration**|
|10278|**AI Skill Config**|
|10279|**Rich Text Attachment**|
|10280|**Custom Control Extended Setting**|
|10281|**Timeline Pin**|
|10282|**Virtual Connector Data Source**|
|10283|**Virtual Table Column Candidate**|
|10285|**PM Analysis History**|
|10286|**PM Business Rule Automation Config**|
|10287|**PM Calendar**|
|10288|**PM Calendar Version**|
|10289|**PM Inferred Task**|
|10290|**PM Process Extended Metadata Version**|
|10291|**PM Process Template**|
|10292|**PM Process User Settings**|
|10293|**PM Process Version**|
|10294|**PM Recording**|
|10295|**PM Simulation**|
|10296|**PM Template**|
|10297|**PM View**|
|10298|**Analysis Component**|
|10299|**Analysis Job**|
|10300|**Analysis Override**|
|10301|**Analysis Result**|
|10302|**Analysis Result Detail**|
|10303|**Solution Health Rule**|
|10304|**Solution Health Rule Argument**|
|10305|**Solution Health Rule Set**|
|10306|**Power BI Dataset**|
|10307|**powerbidatasetapdx**|
|10308|**Power BI Mashup Parameter**|
|10309|**Power BI Report**|
|10310|**powerbireportapdx**|
|10311|**File Upload**|
|10312|**MainFewShot**|
|10313|**MakerFewShot**|
|10314|**SearchAttributeSettings**|
|10315|**SearchCustomAnalyzer**|
|10316|**SearchRelationshipSettings**|
|10317|**SearchResultsCache**|
|10318|**Search Telemetry**|
|10319|**ViewAsExampleQuestion**|
|10320|**CopilotExampleQuestion**|
|10321|**CopilotGlossaryTerm**|
|10322|**CopilotSynonyms**|
|10323|**API Request Cache**|
|10324|**API Request Folder**|
|10325|**Site Component**|
|10326|**Site**|
|10327|**Site Language**|
|10328|**Power Pages Site Published**|
|10331|**External Identity**|
|10332|**Invitation**|
|10333|**Invite Redemption**|
|10334|**Portal Comment**|
|10335|**Setting**|
|10336|**Multistep Form Session**|
|10340|**Ad Placement**|
|10341|**Column Permission**|
|10342|**Column Permission Profile**|
|10343|**Content Snippet**|
|10344|**Basic Form**|
|10345|**Basic Form Metadata**|
|10346|**List**|
|10347|**Table Permission**|
|10348|**Page Template**|
|10349|**Poll Placement**|
|10350|**Power Pages Core Entity DS**|
|10351|**Publishing State**|
|10352|**Publishing State Transition Rule**|
|10353|**Redirect**|
|10354|**Shortcut**|
|10355|**Site Marker**|
|10356|**Site Setting**|
|10357|**Web File**|
|10358|**Multistep Form**|
|10359|**Multistep Form Metadata**|
|10360|**Form Step**|
|10361|**Web Link**|
|10362|**Web Link Set**|
|10363|**Web Page**|
|10364|**Web Page Access Control Rule**|
|10365|**Web Role**|
|10366|**Website**|
|10367|**Website Access**|
|10368|**Website Language**|
|10369|**Web Template**|
|10376|**Power Pages Scan Report**|
|10377|**Power Pages Log**|
|10378|**PowerPagesManagedIdentity**|
|10379|**Power Pages Site AI Feedback**|
|10384|**Catalog Submission Files**|
|10385|**Package Submission Store**|
|10490|**Customer Voice survey**|
|10498|**Staged Source Control Component**|
|10499|**signal**|
|10500|**trait**|
|10561|**Customer Voice survey question**|
|10563|**Customer Voice file response**|
|10564|**Customer Voice survey email template**|
|10573|**Customer Voice survey reminder**|
|10581|**Customer Voice survey question response**|
|10602|**Customer Voice localized survey email template**|
|10606|**Customer Voice satisfaction metric**|
|10607|**Customer Voice unsubscribed recipient**|
|10609|**Customer Voice project**|
|10611|**Customer Voice alert rule**|
|10617|**Copilot Interactions**|
|10618|**Customer Voice alert**|
|10619|**Customer Voice survey invite**|
|10620|**Customer Voice survey response**|
|18085|**Event Expander Breadcrumb**|

### <a name="BKMK_ComponentIdUnique"></a> ComponentIdUnique

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Row id unique**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentidunique`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Component State**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentstate`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue||
|GlobalChoiceName|`componentstate`|

#### ComponentState Choices/Options

|Value|Label|
|---|---|
|0|**Published**|
|1|**Unpublished**|
|2|**Deleted**|
|3|**Deleted Unpublished**|

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who created the duplicate detection rule.**|
|DisplayName|**Created By**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`createdby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Date and time when the duplicate detection rule was created.**|
|DisplayName|**Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the duplicaterule.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|---|---|
|Description|**Indicates whether the solution component is part of a managed solution.**|
|DisplayName|**Is Managed**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ismanaged`|
|RequiredLevel|SystemRequired|
|Type|Boolean|
|GlobalChoiceName|`ismanaged`|
|DefaultValue|False|
|True Label|Managed|
|False Label|Unmanaged|

### <a name="BKMK_MatchingEntityMatchCodeTable"></a> MatchingEntityMatchCodeTable

|Property|Value|
|---|---|
|Description|**Database table that stores match codes for potential duplicate records.**|
|DisplayName|**Matching Record Type Match Code Table**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`matchingentitymatchcodetable`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|50|

### <a name="BKMK_MatchingEntityTypeCode"></a> MatchingEntityTypeCode

|Property|Value|
|---|---|
|Description|**Record type of the records being evaluated as potential duplicates.**|
|DisplayName|**Matching Record Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`matchingentitytypecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`duplicaterule_matchingentitytypecode`|

#### MatchingEntityTypeCode Choices/Options

|Value|Label|
|---|---|
|1|**Account**|
|2|**Contact**|
|5|**Note**|
|6|**Business Unit Map**|
|7|**Owner**|
|8|**User**|
|9|**Team**|
|10|**Business Unit**|
|14|**System User Principal**|
|29|**Subscription**|
|30|**Filter Template**|
|31|**Privilege Object Type Code**|
|33|**Subscription Synchronization Information**|
|35|**Tracking information for deleted entities**|
|36|**Client update**|
|37|**Subscription Manually Tracked Object**|
|42|**SystemUser BusinessUnit Entity Map**|
|44|**Field Sharing**|
|45|**Subscription Statistic Offline**|
|46|**Subscription Statistic Outlook**|
|47|**Subscription Sync Entry Offline**|
|48|**Subscription Sync Entry Outlook**|
|50|**Position**|
|51|**System User Manager Map**|
|52|**User Search Facet**|
|54|**Global Search Configuration**|
|55|**FileAttachment**|
|60|**SystemUserAuthorizationChangeTracker**|
|61|**PrincipalEntityBusinessUnitMap**|
|72|**Record Filter**|
|73|**EntityRecordFilter**|
|74|**Secured Masking Rule**|
|75|**Privilege Checker Run**|
|76|**Privilege Checker Log**|
|78|**Virtual Entity Data Provider**|
|85|**Virtual Entity Data Source**|
|92|**Team template**|
|99|**Social Profile**|
|101|**Service Plan**|
|103|**Privileges Removal Setting**|
|126|**Indexed Article**|
|127|**Article**|
|129|**Subject**|
|132|**Announcement**|
|135|**Activity Party**|
|150|**User Settings**|
|300|**Canvas App**|
|301|**Callback Registration**|
|372|**Connector**|
|373|**Connection Instance**|
|380|**Environment Variable Definition**|
|381|**Environment Variable Value**|
|400|**AI Template**|
|401|**AI Model**|
|402|**AI Configuration**|
|418|**Dataflow**|
|430|**Entity Analytics Config**|
|431|**Image Attribute Configuration**|
|432|**Entity Image Configuration**|
|950|**New Process**|
|951|**Translation Process**|
|955|**Expired Process**|
|1001|**Attachment**|
|1002|**Attachment**|
|1003|**Internal Address**|
|1007|**Image Descriptor**|
|1016|**Article Template**|
|1019|**Organization**|
|1021|**Organization UI**|
|1023|**Privilege**|
|1030|**System Form**|
|1031|**User Dashboard**|
|1036|**Security Role**|
|1037|**Role Template**|
|1039|**View**|
|1043|**String Map**|
|1071|**Address**|
|1072|**Subscription Clients**|
|1075|**Status Map**|
|1082|**Article Comment**|
|1086|**User Fiscal Calendar**|
|1094|**Authorization Server**|
|1095|**Partner Application**|
|1111|**System Chart**|
|1112|**User Chart**|
|1113|**Ribbon Tab To Command Mapping**|
|1115|**Ribbon Context Group**|
|1116|**Ribbon Command**|
|1117|**Ribbon Rule**|
|1120|**Application Ribbons**|
|1130|**Ribbon Difference**|
|1140|**Replication Backlog**|
|1189|**Document Suggestions**|
|1190|**SuggestionCardTemplate**|
|1200|**Field Security Profile**|
|1201|**Field Permission**|
|1203|**Team Profiles**|
|1204|**Application**|
|1234|**Channel Property Group**|
|1236|**Channel Property**|
|1300|**SocialInsightsConfiguration**|
|1309|**Saved Organization Insights Configuration**|
|1400|**Sync Attribute Mapping Profile**|
|1401|**Sync Attribute Mapping**|
|1403|**Team Sync-Attribute Mapping Profiles**|
|1404|**Principal Sync Attribute Map**|
|2000|**Annual Fiscal Calendar**|
|2001|**Semiannual Fiscal Calendar**|
|2002|**Quarterly Fiscal Calendar**|
|2003|**Monthly Fiscal Calendar**|
|2004|**Fixed Monthly Fiscal Calendar**|
|2010|**Email Template**|
|2012|**Unresolved Address**|
|2013|**Territory**|
|2015|**Theme**|
|2016|**User Mapping**|
|2020|**Queue**|
|2023|**QueueItemCount**|
|2024|**QueueMemberCount**|
|2027|**License**|
|2029|**Queue Item**|
|2500|**User Entity UI Settings**|
|2501|**User Entity Instance Data**|
|3000|**Integration Status**|
|3005|**Channel Access Profile**|
|3008|**External Party**|
|3231|**Connection Role**|
|3233|**Connection Role Object Type Code**|
|3234|**Connection**|
|4003|**Calendar**|
|4004|**Calendar Rule**|
|4011|**Inter Process Lock**|
|4023|**Email Hash**|
|4101|**Display String Map**|
|4102|**Display String**|
|4110|**Notification**|
|4120|**Exchange Sync Id Mapping**|
|4200|**Activity**|
|4201|**Appointment**|
|4202|**Email**|
|4204|**Fax**|
|4207|**Letter**|
|4210|**Phone Call**|
|4212|**Task**|
|4216|**Social Activity**|
|4220|**UntrackedEmail**|
|4230|**Saved View**|
|4231|**Metadata Difference**|
|4232|**Business Data Localized Label**|
|4250|**Recurrence Rule**|
|4251|**Recurring Appointment**|
|4299|**Email Search**|
|4410|**Data Import**|
|4411|**Data Map**|
|4412|**Import Source File**|
|4413|**Import Data**|
|4414|**Duplicate Detection Rule**|
|4415|**Duplicate Record**|
|4416|**Duplicate Rule Condition**|
|4417|**Column Mapping**|
|4418|**List Value Mapping**|
|4419|**Lookup Mapping**|
|4420|**Owner Mapping**|
|4423|**Import Log**|
|4424|**Bulk Delete Operation**|
|4425|**Bulk Delete Failure**|
|4426|**Transformation Mapping**|
|4427|**Transformation Parameter Mapping**|
|4428|**Import Entity Mapping**|
|4450|**Data Performance Dashboard**|
|4490|**Office Document**|
|4500|**Relationship Role**|
|4501|**Relationship Role Map**|
|4502|**Customer Relationship**|
|4567|**Auditing**|
|4579|**Ribbon Client Metadata.**|
|4600|**Entity Map**|
|4601|**Attribute Map**|
|4602|**Plug-in Type**|
|4603|**Plug-in Type Statistic**|
|4605|**Plug-in Assembly**|
|4606|**Sdk Message**|
|4607|**Sdk Message Filter**|
|4608|**Sdk Message Processing Step**|
|4609|**Sdk Message Request**|
|4610|**Sdk Message Response**|
|4611|**Sdk Message Response Field**|
|4613|**Sdk Message Pair**|
|4614|**Sdk Message Request Field**|
|4615|**Sdk Message Processing Step Image**|
|4616|**Sdk Message Processing Step Secure Configuration**|
|4618|**Service Endpoint**|
|4619|**Plug-in Trace Log**|
|4700|**System Job**|
|4702|**Workflow Wait Subscription**|
|4703|**Process**|
|4704|**Process Dependency**|
|4705|**ISV Config**|
|4706|**Process Log**|
|4707|**Application File**|
|4708|**Organization Statistic**|
|4709|**Site Map**|
|4710|**Process Session**|
|4711|**Expander Event**|
|4712|**Process Trigger**|
|4720|**Flow Session**|
|4724|**Process Stage**|
|4725|**Business Process Flow Instance**|
|4800|**Web Wizard**|
|4802|**Wizard Page**|
|4803|**Web Wizard Access Privilege**|
|4810|**Time Zone Definition**|
|4811|**Time Zone Rule**|
|4812|**Time Zone Localized Name**|
|5000|**Recently Used**|
|5004|**NL2SQ Registration Information**|
|7000|**System Application Metadata**|
|7001|**User Application Metadata**|
|7100|**Solution**|
|7101|**Publisher**|
|7102|**Publisher Address**|
|7103|**Solution Component**|
|7104|**Solution Component Definition**|
|7105|**Dependency**|
|7106|**Dependency Node**|
|7107|**Invalid Dependency**|
|7108|**Dependency Feature**|
|7200|**RuntimeDependency**|
|7755|**ElasticFileAttachment**|
|8000|**Post**|
|8001|**Post Role**|
|8002|**Post Regarding**|
|8003|**Follow**|
|8005|**Comment**|
|8006|**Like**|
|8040|**ACIViewMapper**|
|8050|**Trace**|
|8051|**Trace Association**|
|8052|**Trace Regarding**|
|8181|**Routing Rule Set**|
|8199|**Rule Item**|
|8700|**AppModule Metadata**|
|8701|**AppModule Metadata Dependency**|
|8702|**AppModule Metadata Async Operation**|
|8840|**Hierarchy Rule**|
|9006|**Model-driven App**|
|9007|**App Module Component**|
|9009|**App Module Roles**|
|9011|**App Config Master**|
|9012|**App Configuration**|
|9013|**App Configuration Instance**|
|9100|**Report**|
|9101|**Report Related Entity**|
|9102|**Report Related Category**|
|9103|**Report Visibility**|
|9104|**Report Link**|
|9105|**Currency**|
|9106|**Mail Merge Template**|
|9107|**Import Job**|
|9201|**LocalConfigStore**|
|9300|**Record Creation and Update Rule**|
|9301|**Record Creation and Update Rule Item**|
|9333|**Web Resource**|
|9400|**Channel Access Profile Rule**|
|9401|**Channel Access Profile Rule Item**|
|9502|**SharePoint Site**|
|9507|**Sharepoint Document**|
|9508|**Document Location**|
|9509|**SharePoint Data**|
|9510|**Rollup Properties**|
|9511|**Rollup Job**|
|9600|**Goal**|
|9602|**Rollup Query**|
|9603|**Goal Metric**|
|9604|**Rollup Field**|
|9605|**Email Server Profile**|
|9606|**Mailbox**|
|9607|**Mailbox Statistics**|
|9608|**Mailbox Auto Tracking Folder**|
|9609|**Mailbox Tracking Category**|
|9650|**Process Configuration**|
|9690|**Organization Insights Notification**|
|9699|**Organization Insights Metric**|
|9750|**SLA**|
|9751|**SLA Item**|
|9752|**SLA KPI Instance**|
|9753|**Custom Control**|
|9754|**Custom Control Resource**|
|9755|**Custom Control Default Config**|
|9800|**Entity**|
|9808|**Attribute**|
|9809|**OptionSet**|
|9810|**Entity Key**|
|9811|**Entity Relationship**|
|9812|**Managed Property**|
|9813|**Relationship Entity**|
|9814|**Relationship Attribute**|
|9815|**Entity Index**|
|9816|**Index Attribute**|
|9820|**Secured Masking Column**|
|9866|**Mobile Offline Profile**|
|9867|**Mobile Offline Profile Item**|
|9868|**Mobile Offline Profile Item Association**|
|9869|**Sync Error**|
|9870|**Offline Command Definition**|
|9875|**Language Provisioning State**|
|9880|**Ribbon Metadata To Process**|
|9890|**SolutionHistoryData**|
|9900|**Navigation Setting**|
|9910|**MultiEntitySearch**|
|9912|**Multi Select Option Value**|
|9919|**Hierarchy Security Configuration**|
|9930|**Knowledge Base Record**|
|9932|**Time Stamp Date Mapping**|
|9936|**Azure Service Connection**|
|9940|**Document Template**|
|9941|**Personal Document Template**|
|9945|**Text Analytics Entity Mapping**|
|9947|**Knowledge Search Model**|
|9949|**Advanced Similarity Rule**|
|9950|**Office Graph Document**|
|9951|**Similarity Rule**|
|9953|**Knowledge Article**|
|9955|**Knowledge Article Views**|
|9957|**Language**|
|9958|**Feedback**|
|9959|**Category**|
|9960|**Knowledge Article Category**|
|9961|**DelveActionHub**|
|9962|**Action Card**|
|9968|**ActionCardUserState**|
|9973|**Action Card User Settings**|
|9983|**Action Card Type**|
|9986|**Interaction for Email**|
|9987|**External Party Item**|
|9996|**HolidayWrapper**|
|9997|**Email Signature**|
|10000|**Solution Component Attribute Configuration**|
|10001|**Solution Component Batch Configuration**|
|10002|**Solution Component Configuration**|
|10003|**Solution Component Relationship Configuration**|
|10004|**Solution History**|
|10005|**Solution History Data Source**|
|10006|**Component Layer**|
|10007|**Component Layer Data Source**|
|10008|**Package**|
|10009|**Package History**|
|10011|**StageSolutionUpload**|
|10012|**ExportSolutionUpload**|
|10013|**FeatureControlSetting**|
|10014|**Solution Component Summary**|
|10015|**Solution Component Count Summary**|
|10016|**Solution Component Data Source**|
|10017|**Solution Component Count Data Source**|
|10018|**Microsoft Entra ID**|
|10019|**Staged Entity**|
|10020|**Staged Entity Attribute**|
|10021|**Staged Metadata Async Operation**|
|10022|**Key Vault Reference**|
|10023|**Managed Identity**|
|10024|**Catalog**|
|10025|**Catalog Assignment**|
|10026|**Internal Catalog Assignment**|
|10027|**Custom API**|
|10028|**Custom API Request Parameter**|
|10029|**Custom API Response Property**|
|10030|**Plugin Package**|
|10031|**NonRelational Data Source**|
|10032|**ProvisionLanguageForUser**|
|10033|**Shared Object**|
|10034|**Shared Workspace**|
|10035|**Shared Workspace Access Token**|
|10036|**Shared Workspace Pool**|
|10037|**Data Lake Folder**|
|10038|**Data Lake Folder Permission**|
|10039|**Data Lake Workspace**|
|10040|**Data Lake Workspace Permission**|
|10041|**Data Processing configuration**|
|10042|**Exported Excel**|
|10043|**RetainedData Excel**|
|10044|**Synapse Database**|
|10045|**Synapse Link External Table State**|
|10046|**Synapse Link Profile**|
|10047|**Synapse Link Profile Entity**|
|10048|**Synapse Link Profile Entity State**|
|10049|**Synapse Link Schedule**|
|10050|**Component Version**|
|10051|**Component Version Data Source**|
|10052|**Component Version (Internal)**|
|10053|**Git Branch**|
|10054|**Git Configuration Retrieval Data Source**|
|10055|**Git Organization**|
|10056|**Git Project**|
|10057|**Git Repository**|
|10058|**Source Control Branch Configuration**|
|10059|**Source Control Component**|
|10060|**Source Control Component Payload**|
|10061|**Source Control Configuration**|
|10062|**DataflowRefreshHistory**|
|10063|**EntityRefreshHistory**|
|10064|**Shared Link Setting**|
|10065|**DelegatedAuthorization**|
|10067|**CascadeGrantRevokeAccessRecordsTracker**|
|10068|**CascadeGrantRevokeAccessVersionTracker**|
|10069|**RevokeInheritedAccessRecordsTracker**|
|10070|**TdsMetadata**|
|10071|**Model-Driven App Element**|
|10072|**Model-Driven App Component Node's Edge**|
|10073|**Model-Driven App Component Node**|
|10074|**Model-Driven App Setting**|
|10075|**Model-Driven App User Setting**|
|10076|**Organization Setting**|
|10077|**Setting Definition**|
|10078|**CanvasApp Extended Metadata**|
|10079|**Service Plan Mapping**|
|10080|**Service Plan Custom Control**|
|10082|**ApplicationUser**|
|10085|**OData v4 Data Source**|
|10086|**Workflow Binary**|
|10087|**Credential**|
|10088|**Desktop Flow Module**|
|10089|**Flow Capacity Assignment**|
|10090|**Flow Credential Application**|
|10091|**Flow Event**|
|10092|**Flow Machine**|
|10093|**Flow Machine Group**|
|10094|**Flow Machine Image**|
|10095|**Flow Machine Image Version**|
|10096|**Flow Machine Network**|
|10097|**ProcessStageParameter**|
|10098|**Work Queue**|
|10099|**Work Queue Item**|
|10100|**Desktop Flow Binary**|
|10101|**Flow Log**|
|10102|**Flow Run**|
|10103|**Action Approval Model**|
|10104|**Approval**|
|10105|**Approval Request**|
|10106|**Approval Response**|
|10107|**Approval Step**|
|10108|**Await All Action Approval Model**|
|10109|**Await All Approval Model**|
|10110|**Basic Approval Model Data**|
|10111|**Flow Approval**|
|10120|**Connection Reference**|
|10121|**DVFileSearch**|
|10122|**DVFileSearchAttribute**|
|10123|**DVFileSearchEntity**|
|10124|**DVTableSearch**|
|10125|**DVTableSearchAttribute**|
|10126|**DVTableSearchEntity**|
|10127|**AICopilot**|
|10128|**AIPluginAuth**|
|10129|**AI Plugin Conversation Starter**|
|10130|**AI Plugin Conversation Starter Mapping**|
|10131|**AI Plugin Governance**|
|10132|**AI Plugin Governance Extended**|
|10133|**AIPluginOperationResponseTemplate**|
|10134|**AIPluginTitle**|
|10135|**SideloadedAIPlugin**|
|10136|**AIPlugin**|
|10137|**AIPluginExternalSchema**|
|10138|**AIPluginExternalSchemaProperty**|
|10139|**AIPluginInstance**|
|10140|**AIPluginOperation**|
|10141|**AIPluginOperationParameter**|
|10142|**AIPluginUserSetting**|
|10144|**AI Event**|
|10145|**AI Builder Feedback Loop**|
|10146|**AI Form Processing Document**|
|10147|**AI Object Detection Image**|
|10148|**AI Object Detection Label**|
|10149|**AI Object Detection Bounding Box**|
|10150|**AI Object Detection Image Mapping**|
|10152|**AI Builder Dataset**|
|10153|**AI Builder Dataset File**|
|10154|**AI Builder Dataset Record**|
|10155|**AI Builder Datasets Container**|
|10156|**AI Builder File**|
|10157|**AI Builder File Attached Data**|
|10158|**Help Page**|
|10159|**Tour**|
|10160|**BotContent**|
|10161|**ConversationTranscript**|
|10162|**Copilot**|
|10163|**Copilot component**|
|10164|**Copilot component collection**|
|10175|**Comment**|
|10176|**Governance Configuration**|
|10177|**Fabric AISkill**|
|10178|**App Insights Metadata**|
|10179|**Dataflow Connection Reference**|
|10180|**Schedule**|
|10181|**Dataflow Template**|
|10182|**Dataflow DatalakeFolder**|
|10183|**Data Movement Service Request**|
|10184|**Data Movement Service Request Status**|
|10185|**DMS Sync Request**|
|10186|**DMS Sync Status**|
|10187|**Knowledge Asset Configuration**|
|10188|**Module Run Detail**|
|10189|**QnA**|
|10190|**Salesforce Structured Object**|
|10191|**Salesforce Structured QnA Config**|
|10192|**Workflow Action Status**|
|10193|**FederatedKnowledgeConfiguration**|
|10194|**FederatedKnowledgeEntityConfiguration**|
|10195|**Form Mapping**|
|10196|**PDF Setting**|
|10197|**Activity File Attachment**|
|10198|**Teams chat**|
|10199|**Service Configuration**|
|10200|**SLA KPI**|
|10201|**Integrated search provider**|
|10202|**Knowledge Management Setting**|
|10203|**Knowledge Federated Article**|
|10204|**Knowledge Federated Article Incident**|
|10205|**Search provider**|
|10206|**Knowledge Article Image**|
|10207|**Knowledge Configuration**|
|10208|**Knowledge Interaction Insight**|
|10209|**Knowledge Search Insight**|
|10210|**Favorite knowledge article**|
|10211|**Knowledge article language setting**|
|10212|**Knowledge Article Attachment**|
|10213|**Knowledge personalization**|
|10214|**Knowledge Article Template**|
|10215|**Knowledge search personal filter config**|
|10216|**Knowledge search filter**|
|10218|**msdyn_historicalcaseharvestbatch**|
|10219|**msdyn_historicalcaseharvestrun**|
|10220|**Knowledge Harvest Job Record**|
|10221|**SupportUserTable**|
|10222|**FxExpression**|
|10223|**Function**|
|10224|**Plug-in**|
|10225|**PowerfxRule**|
|10226|**Planner Business Scenario**|
|10227|**Planner Sync Action**|
|10228|**Ms Graph Resource To Subscription**|
|10229|**Virtual Entity  Metadata**|
|10230|**Background Operation**|
|10231|**Report Parameter**|
|10232|**MobileOfflineProfileExtension**|
|10233|**MobileOfflineProfileItemFilter**|
|10234|**TeamMobileOfflineProfileMembership**|
|10235|**UserMobileOfflineProfileMembership**|
|10236|**OrganizationDataSyncSubscription**|
|10237|**OrganizationDataSyncSubscriptionEntity**|
|10238|**OrganizationDataSyncSubscriptionFnoTable**|
|10239|**OrganizationDataSyncFnoState**|
|10240|**OrganizationDataSyncState**|
|10241|**ArchiveCleanupInfo**|
|10242|**ArchiveCleanupOperation**|
|10243|**BulkArchiveConfig**|
|10244|**BulkArchiveFailureDetail**|
|10245|**BulkArchiveOperation**|
|10246|**BulkArchiveOperationDetail**|
|10247|**EnableArchivalRequest**|
|10248|**MetadataForArchival**|
|10249|**ReconciliationEntityInfo**|
|10250|**ReconciliationEntityStepInfo**|
|10251|**ReconciliationInfo**|
|10252|**RetentionCleanupInfo**|
|10253|**RetentionCleanupOperation**|
|10254|**RetentionConfig**|
|10255|**RetentionFailureDetail**|
|10256|**RetentionOperation**|
|10257|**RetentionOperationDetail**|
|10258|**RetentionSuccessDetail**|
|10259|**CertificateCredential**|
|10260|**Notification**|
|10261|**User Rating**|
|10262|**Mobile App**|
|10263|**Insights Store Data Source**|
|10264|**Insights Store Virtual Entity**|
|10265|**RoleEditorLayout**|
|10266|**Deleted Record Reference**|
|10267|**Restore Deleted Records Configuration**|
|10268|**App Action**|
|10269|**App Action Migration**|
|10270|**App Action Rule**|
|10273|**Card**|
|10274|**Card State Item**|
|10277|**Entity link chat configuration**|
|10278|**AI Skill Config**|
|10279|**Rich Text Attachment**|
|10280|**Custom Control Extended Setting**|
|10281|**Timeline Pin**|
|10282|**Virtual Connector Data Source**|
|10283|**Virtual Table Column Candidate**|
|10285|**PM Analysis History**|
|10286|**PM Business Rule Automation Config**|
|10287|**PM Calendar**|
|10288|**PM Calendar Version**|
|10289|**PM Inferred Task**|
|10290|**PM Process Extended Metadata Version**|
|10291|**PM Process Template**|
|10292|**PM Process User Settings**|
|10293|**PM Process Version**|
|10294|**PM Recording**|
|10295|**PM Simulation**|
|10296|**PM Template**|
|10297|**PM View**|
|10298|**Analysis Component**|
|10299|**Analysis Job**|
|10300|**Analysis Override**|
|10301|**Analysis Result**|
|10302|**Analysis Result Detail**|
|10303|**Solution Health Rule**|
|10304|**Solution Health Rule Argument**|
|10305|**Solution Health Rule Set**|
|10306|**Power BI Dataset**|
|10307|**powerbidatasetapdx**|
|10308|**Power BI Mashup Parameter**|
|10309|**Power BI Report**|
|10310|**powerbireportapdx**|
|10311|**File Upload**|
|10312|**MainFewShot**|
|10313|**MakerFewShot**|
|10314|**SearchAttributeSettings**|
|10315|**SearchCustomAnalyzer**|
|10316|**SearchRelationshipSettings**|
|10317|**SearchResultsCache**|
|10318|**Search Telemetry**|
|10319|**ViewAsExampleQuestion**|
|10320|**CopilotExampleQuestion**|
|10321|**CopilotGlossaryTerm**|
|10322|**CopilotSynonyms**|
|10323|**API Request Cache**|
|10324|**API Request Folder**|
|10325|**Site Component**|
|10326|**Site**|
|10327|**Site Language**|
|10328|**Power Pages Site Published**|
|10331|**External Identity**|
|10332|**Invitation**|
|10333|**Invite Redemption**|
|10334|**Portal Comment**|
|10335|**Setting**|
|10336|**Multistep Form Session**|
|10340|**Ad Placement**|
|10341|**Column Permission**|
|10342|**Column Permission Profile**|
|10343|**Content Snippet**|
|10344|**Basic Form**|
|10345|**Basic Form Metadata**|
|10346|**List**|
|10347|**Table Permission**|
|10348|**Page Template**|
|10349|**Poll Placement**|
|10350|**Power Pages Core Entity DS**|
|10351|**Publishing State**|
|10352|**Publishing State Transition Rule**|
|10353|**Redirect**|
|10354|**Shortcut**|
|10355|**Site Marker**|
|10356|**Site Setting**|
|10357|**Web File**|
|10358|**Multistep Form**|
|10359|**Multistep Form Metadata**|
|10360|**Form Step**|
|10361|**Web Link**|
|10362|**Web Link Set**|
|10363|**Web Page**|
|10364|**Web Page Access Control Rule**|
|10365|**Web Role**|
|10366|**Website**|
|10367|**Website Access**|
|10368|**Website Language**|
|10369|**Web Template**|
|10376|**Power Pages Scan Report**|
|10377|**Power Pages Log**|
|10378|**PowerPagesManagedIdentity**|
|10379|**Power Pages Site AI Feedback**|
|10384|**Catalog Submission Files**|
|10385|**Package Submission Store**|
|10490|**Customer Voice survey**|
|10498|**Staged Source Control Component**|
|10499|**signal**|
|10500|**trait**|
|10561|**Customer Voice survey question**|
|10563|**Customer Voice file response**|
|10564|**Customer Voice survey email template**|
|10573|**Customer Voice survey reminder**|
|10581|**Customer Voice survey question response**|
|10602|**Customer Voice localized survey email template**|
|10606|**Customer Voice satisfaction metric**|
|10607|**Customer Voice unsubscribed recipient**|
|10609|**Customer Voice project**|
|10611|**Customer Voice alert rule**|
|10617|**Copilot Interactions**|
|10618|**Customer Voice alert**|
|10619|**Customer Voice survey invite**|
|10620|**Customer Voice survey response**|
|18085|**Event Expander Breadcrumb**|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who last modified the duplicate detection rule.**|
|DisplayName|**Modified By**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`modifiedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Date and time when the duplicate detection rule was last modified.**|
|DisplayName|**Modified On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who last modified the duplicaterule.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Record Overwrite Time**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overwritetime`|
|RequiredLevel|SystemRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridname`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridyominame`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|---|---|
|Description|**Unique identifier of the business unit that owns duplicate detection rule.**|
|DisplayName||
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`owningbusinessunit`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|businessunit|

### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|---|---|
|Description|**Unique identifier of the team who owns the duplicate detection rule.**|
|DisplayName|**Owning Team**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owningteam`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|team|

### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who owns the duplicate detection rule.**|
|DisplayName|**Owning User**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owninguser`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|---|---|
|Description|**Unique identifier of the associated solution.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`solutionid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_StateCode"></a> StateCode

|Property|Value|
|---|---|
|Description|**Status of the duplicate detection rule.**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue|0|
|GlobalChoiceName|`duplicaterule_statecode`|

#### StateCode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Inactive**<br />DefaultStatus: 0<br />InvariantName: `Inactive`|
|1|Label: **Active**<br />DefaultStatus: 2<br />InvariantName: `Active`|

### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|`supportingsolutionid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [BusinessUnit_DuplicateRules](#BKMK_BusinessUnit_DuplicateRules)
- [lk_duplicaterule_createdonbehalfby](#BKMK_lk_duplicaterule_createdonbehalfby)
- [lk_duplicaterule_modifiedonbehalfby](#BKMK_lk_duplicaterule_modifiedonbehalfby)
- [lk_duplicaterulebase_createdby](#BKMK_lk_duplicaterulebase_createdby)
- [lk_duplicaterulebase_modifiedby](#BKMK_lk_duplicaterulebase_modifiedby)
- [owner_duplicaterules](#BKMK_owner_duplicaterules)
- [SystemUser_DuplicateRules](#BKMK_SystemUser_DuplicateRules)
- [team_DuplicateRules](#BKMK_team_DuplicateRules)

### <a name="BKMK_BusinessUnit_DuplicateRules"></a> BusinessUnit_DuplicateRules

One-To-Many Relationship: [businessunit BusinessUnit_DuplicateRules](businessunit.md#BKMK_BusinessUnit_DuplicateRules)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_duplicaterule_createdonbehalfby"></a> lk_duplicaterule_createdonbehalfby

One-To-Many Relationship: [systemuser lk_duplicaterule_createdonbehalfby](systemuser.md#BKMK_lk_duplicaterule_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_duplicaterule_modifiedonbehalfby"></a> lk_duplicaterule_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_duplicaterule_modifiedonbehalfby](systemuser.md#BKMK_lk_duplicaterule_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_duplicaterulebase_createdby"></a> lk_duplicaterulebase_createdby

One-To-Many Relationship: [systemuser lk_duplicaterulebase_createdby](systemuser.md#BKMK_lk_duplicaterulebase_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_duplicaterulebase_modifiedby"></a> lk_duplicaterulebase_modifiedby

One-To-Many Relationship: [systemuser lk_duplicaterulebase_modifiedby](systemuser.md#BKMK_lk_duplicaterulebase_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_duplicaterules"></a> owner_duplicaterules

One-To-Many Relationship: [owner owner_duplicaterules](owner.md#BKMK_owner_duplicaterules)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_SystemUser_DuplicateRules"></a> SystemUser_DuplicateRules

One-To-Many Relationship: [systemuser SystemUser_DuplicateRules](systemuser.md#BKMK_SystemUser_DuplicateRules)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`owninguser`|
|ReferencingEntityNavigationPropertyName|`owninguser`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_DuplicateRules"></a> team_DuplicateRules

One-To-Many Relationship: [team team_DuplicateRules](team.md#BKMK_team_DuplicateRules)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [DuplicateRule_Annotation](#BKMK_DuplicateRule_Annotation)
- [DuplicateRule_DuplicateBaseRecord](#BKMK_DuplicateRule_DuplicateBaseRecord)
- [DuplicateRule_DuplicateRuleConditions](#BKMK_DuplicateRule_DuplicateRuleConditions)
- [DuplicateRule_SyncErrors](#BKMK_DuplicateRule_SyncErrors)

### <a name="BKMK_DuplicateRule_Annotation"></a> DuplicateRule_Annotation

Many-To-One Relationship: [annotation DuplicateRule_Annotation](annotation.md#BKMK_DuplicateRule_Annotation)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`DuplicateRule_Annotation`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_DuplicateRule_DuplicateBaseRecord"></a> DuplicateRule_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord DuplicateRule_DuplicateBaseRecord](duplicaterecord.md#BKMK_DuplicateRule_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicateruleid`|
|ReferencedEntityNavigationPropertyName|`DuplicateRule_DuplicateBaseRecord`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_DuplicateRule_DuplicateRuleConditions"></a> DuplicateRule_DuplicateRuleConditions

Many-To-One Relationship: [duplicaterulecondition DuplicateRule_DuplicateRuleConditions](duplicaterulecondition.md#BKMK_DuplicateRule_DuplicateRuleConditions)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterulecondition`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`DuplicateRule_DuplicateRuleConditions`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_DuplicateRule_SyncErrors"></a> DuplicateRule_SyncErrors

Many-To-One Relationship: [syncerror DuplicateRule_SyncErrors](syncerror.md#BKMK_DuplicateRule_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`DuplicateRule_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.duplicaterule?displayProperty=fullName>
