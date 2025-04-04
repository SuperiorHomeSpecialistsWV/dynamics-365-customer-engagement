---
title: "msdyn_ocvoicechannelsetting Entity Reference (Microsoft Dataverse)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_ocvoicechannelsetting entity."
ms.date: 11/01/2022
ms.topic: "reference"
author: "gandhamm"
ms.author: "mgandham"
ms.reviewer: "mgandham"
---

# msdyn_ocvoicechannelsetting Entity Reference

[!INCLUDE[cc-use-with-omnichannel](../../../../includes/cc-use-with-omnichannel.md)]

**Added by**: Omnichannel - Telephony Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings(*msdyn_ocvoicechannelsettingid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|CreateMultiple||`Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest`|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings(*msdyn_ocvoicechannelsettingid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|msdyn_TelephonyVoiceChannelProvisionAction| Microsoft.Dynamics.CRM.msdyn_TelephonyVoiceChannelProvisionAction |Type generated by CrmSvcUtil.exe or use Microsoft.Xrm.Sdk.OrganizationRequest setting the required parameters for the message. |
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings(*msdyn_ocvoicechannelsettingid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings(*msdyn_ocvoicechannelsettingid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_ocvoicechannelsettings(*msdyn_ocvoicechannelsettingid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|
|UpdateMultiple||`Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest`|

## Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_ocvoicechannelsettings|
|DisplayCollectionName|Voice Channel Settings|
|DisplayName|Voice Channel Setting|
|EntitySetName|msdyn_ocvoicechannelsettings|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_ocvoicechannelsettings|
|LogicalName|msdyn_ocvoicechannelsetting|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_ocvoicechannelsettingid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_ocvoicechannelsetting|

<a name="writable-attributes"></a>

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_agentexternalparticipantcontrolenabled](#BKMK_msdyn_agentexternalparticipantcontrolenabled)
- [msdyn_agentexternalteamsparticipantcontrolenabled](#BKMK_msdyn_agentexternalteamsparticipantcontrolenabled)
- [msdyn_agentrecordingcontrolsenabled](#BKMK_msdyn_agentrecordingcontrolsenabled)
- [msdyn_agenttranscriptioncontrolsenabled](#BKMK_msdyn_agenttranscriptioncontrolsenabled)
- [msdyn_announceaveragewaittime](#BKMK_msdyn_announceaveragewaittime)
- [msdyn_announcepositioninqueue](#BKMK_msdyn_announcepositioninqueue)
- [msdyn_inboundurl](#BKMK_msdyn_inboundurl)
- [msdyn_liveworkstreamid](#BKMK_msdyn_liveworkstreamid)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_ocvoicechannelsettingId](#BKMK_msdyn_ocvoicechannelsettingId)
- [msdyn_operatinghoursid](#BKMK_msdyn_operatinghoursid)
- [msdyn_phonenumberid](#BKMK_msdyn_phonenumberid)
- [msdyn_recordingenabled](#BKMK_msdyn_recordingenabled)
- [msdyn_recordingmode](#BKMK_msdyn_recordingmode)
- [msdyn_transcriptionenabled](#BKMK_msdyn_transcriptionenabled)
- [msdyn_transcriptionmode](#BKMK_msdyn_transcriptionmode)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_agentexternalparticipantcontrolenabled"></a> msdyn_agentexternalparticipantcontrolenabled

|Property|Value|
|--------|-----|
|Description|Enable agent control to add an external participant|
|DisplayName|Enable agent control to add an external participant|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_agentexternalparticipantcontrolenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_agentexternalparticipantcontrolenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_agentexternalteamsparticipantcontrolenabled"></a> msdyn_agentexternalteamsparticipantcontrolenabled

|Property|Value|
|--------|-----|
|Description|Enable agent control to add an external participant on Teams|
|DisplayName|Enable agent control to add an external participant on Teams|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_agentexternalteamsparticipantcontrolenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_agentexternalteamsparticipantcontrolenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_agentrecordingcontrolsenabled"></a> msdyn_agentrecordingcontrolsenabled

|Property|Value|
|--------|-----|
|Description|Enable agent control of the recording|
|DisplayName|Enable agent control of the recording|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_agentrecordingcontrolsenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_agentrecordingcontrolsenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_agenttranscriptioncontrolsenabled"></a> msdyn_agenttranscriptioncontrolsenabled

|Property|Value|
|--------|-----|
|Description|Enable agent control of the transcription|
|DisplayName|Enable agent control of the transcription|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_agenttranscriptioncontrolsenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_agenttranscriptioncontrolsenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_announceaveragewaittime"></a> msdyn_announceaveragewaittime

|Property|Value|
|--------|-----|
|Description|Announce the average wait time of the customer in queue|
|DisplayName|Announce average wait time|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_announceaveragewaittime|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_announceaveragewaittime Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_announcepositioninqueue"></a> msdyn_announcepositioninqueue

|Property|Value|
|--------|-----|
|Description|Announce the position of the customer in queue|
|DisplayName|Announce position in queue|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_announcepositioninqueue|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_announcepositioninqueue Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_inboundurl"></a> msdyn_inboundurl

|Property|Value|
|--------|-----|
|Description|Inbound URL|
|DisplayName|Inbound URL|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_inboundurl|
|MaxLength|500|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_liveworkstreamid"></a> msdyn_liveworkstreamid

|Property|Value|
|--------|-----|
|Description|Work Stream|
|DisplayName|Work Stream|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_liveworkstreamid|
|RequiredLevel|None|
|Targets|msdyn_liveworkstream|
|Type|Lookup|


### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|--------|-----|
|Description|The name of the custom entity.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_ocvoicechannelsettingId"></a> msdyn_ocvoicechannelsettingId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Voice Channel Setting|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_ocvoicechannelsettingid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_operatinghoursid"></a> msdyn_operatinghoursid

|Property|Value|
|--------|-----|
|Description|Operating Hours|
|DisplayName|Operating Hours|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_operatinghoursid|
|RequiredLevel|None|
|Targets|msdyn_operatinghour|
|Type|Lookup|


### <a name="BKMK_msdyn_phonenumberid"></a> msdyn_phonenumberid

|Property|Value|
|--------|-----|
|Description|Phone Number|
|DisplayName|Phone Number|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_phonenumberid|
|RequiredLevel|None|
|Targets|msdyn_ocphonenumber|
|Type|Lookup|


### <a name="BKMK_msdyn_recordingenabled"></a> msdyn_recordingenabled

|Property|Value|
|--------|-----|
|Description|Recording Enabled|
|DisplayName|Recording Enabled|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_recordingenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_recordingenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_recordingmode"></a> msdyn_recordingmode

|Property|Value|
|--------|-----|
|Description|Recording mode|
|DisplayName|Recording mode|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_recordingmode|
|RequiredLevel|None|
|Type|MultiSelectPicklist|

#### msdyn_recordingmode Choices/Options

|Value|Label|Description|
|-----|-----|-----|
|192351000|None|Feature is disabled|
|192351001|Manual|Feature is enabled/disabled manually|
|192351002|Automatic|Feature enable and disable is automatically managed|



### <a name="BKMK_msdyn_transcriptionenabled"></a> msdyn_transcriptionenabled

|Property|Value|
|--------|-----|
|Description|Transcription Enabled|
|DisplayName|Transcription Enabled|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_transcriptionenabled|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_transcriptionenabled Choices/Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_transcriptionmode"></a> msdyn_transcriptionmode

|Property|Value|
|--------|-----|
|Description|Transcription mode|
|DisplayName|Transcription mode|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_transcriptionmode|
|RequiredLevel|None|
|Type|MultiSelectPicklist|

#### msdyn_transcriptionmode Choices/Options

|Value|Label|Description|
|-----|-----|-----|
|192351000|None|Feature is disabled|
|192351001|Manual|Feature is enabled/disabled manually|
|192351002|Automatic|Feature enable and disable is automatically managed|



### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|--------|-----|
|Description|Status of the Voice Channel Setting|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### statecode Choices/Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Active|1|Active|
|1|Inactive|2|Inactive|



### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the Voice Channel Setting|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### statuscode Choices/Options

|Value|Label|State|
|-----|-----|-----|
|1|Active|0|
|2|Inactive|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_liveworkstreamidName](#BKMK_msdyn_liveworkstreamidName)
- [msdyn_operatinghoursidName](#BKMK_msdyn_operatinghoursidName)
- [msdyn_phonenumberidName](#BKMK_msdyn_phonenumberidName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningBusinessUnitName](#BKMK_OwningBusinessUnitName)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_liveworkstreamidName"></a> msdyn_liveworkstreamidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_liveworkstreamidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_operatinghoursidName"></a> msdyn_operatinghoursidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_operatinghoursidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_phonenumberidName"></a> msdyn_phonenumberidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_phonenumberidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
|DisplayName|Owning Business Unit|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningBusinessUnitName"></a> OwningBusinessUnitName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunitname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the team that owns the record.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|


### Related information

[About the Entity Reference](../../../../customerengagement/on-premises/developer/about-entity-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
