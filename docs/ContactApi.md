# swagger_client.ContactApi

All URIs are relative to *https://localhost:7207/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**contact_get**](ContactApi.md#contact_get) | **GET** /contact | 
[**contact_id_delete**](ContactApi.md#contact_id_delete) | **DELETE** /contact/{id} | 
[**contact_id_get**](ContactApi.md#contact_id_get) | **GET** /contact/{id} | 
[**contact_id_put**](ContactApi.md#contact_id_put) | **PUT** /contact/{id} | 
[**contact_post**](ContactApi.md#contact_post) | **POST** /contact | 

# **contact_get**
> list[Contact] contact_get()



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.ContactApi()

try:
    api_response = api_instance.contact_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ContactApi->contact_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[Contact]**](Contact.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contact_id_delete**
> list[Contact] contact_id_delete(id)



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.ContactApi()
id = 56 # int | 

try:
    api_response = api_instance.contact_id_delete(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ContactApi->contact_id_delete: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  | 

### Return type

[**list[Contact]**](Contact.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contact_id_get**
> Contact contact_id_get(id)



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.ContactApi()
id = 56 # int | 

try:
    api_response = api_instance.contact_id_get(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ContactApi->contact_id_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  | 

### Return type

[**Contact**](Contact.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contact_id_put**
> list[Contact] contact_id_put(id, body=body)



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.ContactApi()
id = 56 # int | 
body = swagger_client.Contact() # Contact |  (optional)

try:
    api_response = api_instance.contact_id_put(id, body=body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ContactApi->contact_id_put: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  | 
 **body** | [**Contact**](Contact.md)|  | [optional] 

### Return type

[**list[Contact]**](Contact.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contact_post**
> list[Contact] contact_post(body=body)



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.ContactApi()
body = swagger_client.Contact() # Contact |  (optional)

try:
    api_response = api_instance.contact_post(body=body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ContactApi->contact_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**Contact**](Contact.md)|  | [optional] 

### Return type

[**list[Contact]**](Contact.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

