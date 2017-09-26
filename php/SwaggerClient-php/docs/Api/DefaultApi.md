# Swagger\Client\DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/JTL-API/JTL-Article-Data/0.0.1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**articleGet**](DefaultApi.md#articleGet) | **GET** /article | 
[**dataRequest**](DefaultApi.md#dataRequest) | **GET** /article/{id}/data_request | 


# **articleGet**
> \Swagger\Client\Model\InlineResponse200 articleGet()



Artikel Information

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\DefaultApi();

try {
    $result = $api_instance->articleGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->articleGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\InlineResponse200**](../Model/InlineResponse200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **dataRequest**
> \Swagger\Client\Model\InlineResponse2001 dataRequest($id)



returns the articledata

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\DefaultApi();
$id = "id_example"; // string | the id of the article

try {
    $result = $api_instance->dataRequest($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->dataRequest: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**| the id of the article |

### Return type

[**\Swagger\Client\Model\InlineResponse2001**](../Model/InlineResponse2001.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

