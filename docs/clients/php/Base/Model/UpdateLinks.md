# # UpdateLinks

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**table_id** | **string** | The id of the table. The id of a table is unique inside a base and is often used to identify a table. **Important: the table_id is not the table_name**. |
**other_table_id** | **string** | The id of the table. The id of a table is unique inside a base and is often used to identify a table. **Important: the table_id is not the table_name**. |
**link_id** | **string** | Every *link column* has a &#x60;key&#x60; and &#x60;link_id&#x60; in the column object. Use [Get Metadata](/reference/get-metadata) or [Get Base Info](/reference/get-base-info) to get this &#x60;link_id&#x60;. Don&#39;t use the &#x60;key&#x60; of the link column. |
**row_id_list** | **string[]** | List of the source rows IDs whose links you&#39;d like to update. |
**other_rows_ids_map** | **string[]** | Map of IDs of the target rows which you&#39;d like to link your source rows to. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)