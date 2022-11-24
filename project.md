
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") nocode_utils

Some tools for No Code Studio

<details><summary><span style="color:DarkGoldenRod"><i>References</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/references/images/XsdSchemaReference_16x16.png?raw=true "ImportXsdSchemaReference") CouchDb_schema


see [documentation](http://localhost:18080/convertigo/xsd/couchdb/CouchDb.xsd)
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


<details><summary><b>c8oforms_fs</b></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/fullsyncconnector_color_16x16.png?raw=true "FullSyncConnector") c8oforms_fs



<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


<details><summary><b>get_view</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/couchdb/images/getview_color_16x16.png?raw=true "GetViewTransaction") get_view



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;_use_ddoc
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;_use_keys
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;_use_view
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>GetServerInfo</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/couchdb/images/getserverinfo_color_16x16.png?raw=true "GetServerInfoTransaction") GetServerInfo


</p></blockquote></details>

<details><summary><b>PostBulkDocuments</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/couchdb/images/postbulkdocuments_color_16x16.png?raw=true "PostBulkDocumentsTransaction") PostBulkDocuments



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/multivaluedvariable_color_16x16.png?raw=true "  alt="RequestableMultiValuedVariable" >&nbsp;data
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>
</p></blockquote></details>

<details><summary><b>c8oforms_response_fs</b></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/fullsyncconnector_color_16x16.png?raw=true "FullSyncConnector") c8oforms_response_fs



<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


<details><summary><b>date_responses_view</b> : <div>Dates of form responses for a specific version</div></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/couchdb/images/getview_color_16x16.png?raw=true "GetViewTransaction") date_responses_view

<div>Dates of form responses for a specific version</div>

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;_use_key
</td>
<td>
<div>Array containing the id of the response form and the version number</div>
</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>GetServerInfo</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/couchdb/images/getserverinfo_color_16x16.png?raw=true "GetServerInfoTransaction") GetServerInfo


</p></blockquote></details>
</p></blockquote></details>
</p></blockquote></details>

<details><summary><b>void</b> : void connector, replace or don't use it</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Sequences</i></span></summary><blockquote><p>


<details><summary><b>delete_published_by_list</b> : Delete list of published forms</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") delete_published_by_list

Delete list of published forms.

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;allow_empty
</td>
<td>
Authorize or not empty list to remove all published forms
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;do_delete
</td>
<td>
Security variable to enable doc deletion
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/multivaluedvariable_color_16x16.png?raw=true "  alt="RequestableMultiValuedVariable" >&nbsp;keys
</td>
<td>
Array of published forms id
</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>get_all_published</b> : Get all published forms</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") get_all_published

Get all published forms.
</p></blockquote></details>
</p></blockquote></details>
