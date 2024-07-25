# IoDocumentEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifies the event. | 
**Source** | **string** |  | 
**Specversion** | **string** | The version of the CloudEvents specification which the event uses. | 
**Type** | **string** |  | [default to "IoDocument"]
**Datacontenttype** | Pointer to **string** | Content type of the data value. Must adhere to RFC 2046 format. | [optional] 
**Dataschema** | Pointer to **string** | Identifies the schema that data adheres to. | [optional] 
**Subject** | Pointer to **string** |  | [optional] [default to "IoDocument"]
**Time** | Pointer to **time.Time** | Timestamp of when the occurrence happened. Must adhere to RFC 3339. | [optional] 
**Data** | Pointer to [**IoDocument**](IoDocument.md) |  | [optional] 
**DataBase64** | Pointer to **string** | Base64 encoded event payload. Must adhere to RFC4648. | [optional] 

## Methods

### NewIoDocumentEvent

`func NewIoDocumentEvent(id string, source string, specversion string, type_ string, ) *IoDocumentEvent`

NewIoDocumentEvent instantiates a new IoDocumentEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIoDocumentEventWithDefaults

`func NewIoDocumentEventWithDefaults() *IoDocumentEvent`

NewIoDocumentEventWithDefaults instantiates a new IoDocumentEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IoDocumentEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IoDocumentEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IoDocumentEvent) SetId(v string)`

SetId sets Id field to given value.


### GetSource

`func (o *IoDocumentEvent) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *IoDocumentEvent) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *IoDocumentEvent) SetSource(v string)`

SetSource sets Source field to given value.


### GetSpecversion

`func (o *IoDocumentEvent) GetSpecversion() string`

GetSpecversion returns the Specversion field if non-nil, zero value otherwise.

### GetSpecversionOk

`func (o *IoDocumentEvent) GetSpecversionOk() (*string, bool)`

GetSpecversionOk returns a tuple with the Specversion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecversion

`func (o *IoDocumentEvent) SetSpecversion(v string)`

SetSpecversion sets Specversion field to given value.


### GetType

`func (o *IoDocumentEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *IoDocumentEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *IoDocumentEvent) SetType(v string)`

SetType sets Type field to given value.


### GetDatacontenttype

`func (o *IoDocumentEvent) GetDatacontenttype() string`

GetDatacontenttype returns the Datacontenttype field if non-nil, zero value otherwise.

### GetDatacontenttypeOk

`func (o *IoDocumentEvent) GetDatacontenttypeOk() (*string, bool)`

GetDatacontenttypeOk returns a tuple with the Datacontenttype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacontenttype

`func (o *IoDocumentEvent) SetDatacontenttype(v string)`

SetDatacontenttype sets Datacontenttype field to given value.

### HasDatacontenttype

`func (o *IoDocumentEvent) HasDatacontenttype() bool`

HasDatacontenttype returns a boolean if a field has been set.

### GetDataschema

`func (o *IoDocumentEvent) GetDataschema() string`

GetDataschema returns the Dataschema field if non-nil, zero value otherwise.

### GetDataschemaOk

`func (o *IoDocumentEvent) GetDataschemaOk() (*string, bool)`

GetDataschemaOk returns a tuple with the Dataschema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataschema

`func (o *IoDocumentEvent) SetDataschema(v string)`

SetDataschema sets Dataschema field to given value.

### HasDataschema

`func (o *IoDocumentEvent) HasDataschema() bool`

HasDataschema returns a boolean if a field has been set.

### GetSubject

`func (o *IoDocumentEvent) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *IoDocumentEvent) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *IoDocumentEvent) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *IoDocumentEvent) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetTime

`func (o *IoDocumentEvent) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *IoDocumentEvent) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *IoDocumentEvent) SetTime(v time.Time)`

SetTime sets Time field to given value.

### HasTime

`func (o *IoDocumentEvent) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetData

`func (o *IoDocumentEvent) GetData() IoDocument`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *IoDocumentEvent) GetDataOk() (*IoDocument, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *IoDocumentEvent) SetData(v IoDocument)`

SetData sets Data field to given value.

### HasData

`func (o *IoDocumentEvent) HasData() bool`

HasData returns a boolean if a field has been set.

### GetDataBase64

`func (o *IoDocumentEvent) GetDataBase64() string`

GetDataBase64 returns the DataBase64 field if non-nil, zero value otherwise.

### GetDataBase64Ok

`func (o *IoDocumentEvent) GetDataBase64Ok() (*string, bool)`

GetDataBase64Ok returns a tuple with the DataBase64 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataBase64

`func (o *IoDocumentEvent) SetDataBase64(v string)`

SetDataBase64 sets DataBase64 field to given value.

### HasDataBase64

`func (o *IoDocumentEvent) HasDataBase64() bool`

HasDataBase64 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


