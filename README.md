| Name | Type | Description |
| --- | --- | --- |
| `name` | string | The connection name |
| `description` | string | The description of the connection |
| `owner` | container | The details of the owner of the connection. Contains the `imsUserId`, `ownerId`, `name`, and `type` parameters. |
| `imsUserId` | string | The IMS user ID of the owner |
| `ownerId` | string | The ID of the owner |
| `name` | string | The name of the owner |
| `type` | string | The type of user that owns the connection |
| `dataSets` | container | The information related to the data sets. Contains the `dataSetId`, `domain`, `type`, `timestampId`, `visitorId`, `lookupKeyField`, `lookupParentFields`, `lookupParentDataSetId`, `lookupParentDataSetType`, `identityNamespace`, `usePrimaryIdNamespace`, `identityMap`, `name`, `schemaInfo`, `streaming`, `backfillSummary`, `lastIngestedTime`, `streamingEnabledAt`, `identityNamespaceCol`, and `dataSourceType` parameters. |
| `dataSetId` | string | The data set ID |
| `domain` | string | The domain of the data set |
| `type` | string | The type of data set |
| `timestampId` | string | The ID used for the timestamp |
| `visitorId` | string | The visitor ID |
| `lookupKeyField` | string | The key field used by a lookup data set. This field only applies to a lookup data set. |
| `lookupParentFields` | string | The parent fields used by a lookup data set. This field only applies to a lookup data set. |
| `lookupParentDataSetId` | string | The parent data set ID used by a lookup data set. This field only applies to a lookup data set. |
| `lookupParentDataSetType` | string | The type of parent data set used by a lookup data set. This field only applies to a lookup data set. |
| `identityNamespace` | string | The namespace used by the connection. Please reference the [Create a Connection](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/create-connection.html) documentation for more information regarding Namespaces and Identity Map. |
| `usePrimaryIdNamespace` | boolean | Whether the primary ID namespace is used |
| `identityMap` | boolean | Whether the identity map is used |
| `name` | string | The name of the data set |
| `schemaInfo` | container | The information of the given schema. Contains the `schemaId`, `schemaName`, and `schemaRef` parameters. |
| `schemaId` | string | The schema ID |
| `schemaName` | string | The schema name |
| `schemaRef` | container | Contains the `id`, and `contentType` parameters. |
| `id` | string | The ID |
| `contentType` | string | The type of content |
| `backfills` | container | Backfills that have been performed with the data. Contains the `id`, `dataSetId`, `status`, `startDate`, `endDate`, `createdDate`, and `allData` parameters. |
| `id` | string | The ID of the backfill |
| `dataSetId` | string | The data set ID |
| `status` | string | The status of the backfill |
| `startDate` | string | The starting date of the backfilled data |
| `endDate` | string | The ending date of the backfilled data |
| `createdDate` | string | The date the backfill was created |
| `allData` | boolean | Whether all data is displayed |
| `streaming` | boolean | Whether streaming is enabled |
| `backfillSummary` | container | A summary of all attempted backfills. Contains the `total`, `failed`, `inProgress`, `completed`, and `invalid` parameters. |
| `total` | integer | The number of backfills attempted |
| `failed` | integer | The number of backfills that failed |
| `inProgress` | integer | The number of backfills in progress |
| `completed` | integer | The number of backfills completed |
| `invalid` | boolean | The number of invalid backfills |
| `lastIngestedTime` | string |  |
| `streamingEnabledAt` | string |  |
| `identityNamespaceCol` | string |  |
| `dataSourceType` | container | Information about the data source type. Contains the `id`, `type`, and `description` parameters. |
| `id` | string | The ID of the data source |
| `type` | string | The type of the data source |
| `description` | string | The description of the data source |
| `identityNamespaceData` | container | Contains the `dataSetId`, `domain`, `identityNamespace`, `usePrimaryIdNamespace`, `identityMap`, and `identityNamespaceCol` parameters. |
| `dataSetId` | string | The data set ID |
| `domain` | string |  |
| `identityNamespaceCol` | string |  |
| `modifiedDate` | string | The date when the connection was last modified |
| `createdDate` | string | The date the connection was created |
| `organization` | string | The org ID the connection belongs to |
| `modifiedBy` | string | The user ID of the person who last modified the connection |
| `modifiedByFullName` | string | The name of the person who last modified the connection |
| `caseSensitive` | boolean | Whether the connection is case sensitive |
| `numDailyEvents` | integer | The number of daily events associated with the connection |
| `externalData` | container | External data associated with the connection. Contains the `externalId`, and `externalParentId` parameters. |
| `externalId` | string | The external ID of the connection |
| `externalParentId` | string | The external ID of the connection |
| `backfillEnabled` | boolean | Whether backfill is enabled |
| `sandboxId` | string | The sandbox ID |
| `sandboxName` | string | The sandbox name |
| `fieldsId` | string | The fields ID |
| `floatPrecision` | integer | The float precision |
| `dataRetentionMonths` | integer | For how many months data is retained prior to being removed |
| `connectionValidationErrors` | container | Any errors associated with the connection validation. Contains the `errorCode`, `dataSetId`, `dataSetName`, `disallowedField`, and `missingField` parameters. |
| `errorCode` | string | A given error code |
| `dataSetId` | string | The data set ID |
| `dataSetName` | string | The data set name |
| `disallowedField` | string | A field that is not allowed |
| `missingField` | string | A field that is missing |
| `backfillSummary` | container | A summary of all attempted backfills. Contains the `total`, `failed`, `inProgress`, `completed`, and `invalid` parameters. |
| `total` | integer | The number of backfills attempted |
| `failed` | integer | The number of backfills that failed |
| `inProgress` | integer | The number of backfills in progress |
| `completed` | integer | The number of backfills completed |
| `invalid` | boolean | The number of invalid backfills |
| `idWithoutPrefix` | string | The ID of the connection without the `dg_` prefix |
| `id` | string | The connection ID |
