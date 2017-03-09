# Swagger\Client\ActionApi

All URIs are relative to *https://api.unwaffle.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addAction**](ActionApi.md#addAction) | **POST** /action | Add an action


# **addAction**
> addAction($body)

Add an action



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure HTTP basic authorization: basicAuth
Swagger\Client\Configuration::getDefaultConfiguration()->setUsername('YOUR_USERNAME');
Swagger\Client\Configuration::getDefaultConfiguration()->setPassword('YOUR_PASSWORD');

$api_instance = new Swagger\Client\Api\ActionApi();
$body = new \Swagger\Client\Model\TransportObject(); // \Swagger\Client\Model\TransportObject | A TransportObject describing the action. The API will also happily consume a CSV or TSV with one record per line and no header row.

try {
    $api_instance->addAction($body);
} catch (Exception $e) {
    echo 'Exception when calling ActionApi->addAction: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Swagger\Client\Model\TransportObject**](../Model/\Swagger\Client\Model\TransportObject.md)| A TransportObject describing the action. The API will also happily consume a CSV or TSV with one record per line and no header row. | [optional]

### Return type

void (empty response body)

### Authorization

[basicAuth](../../README.md#basicAuth)

### HTTP request headers

 - **Content-Type**: application/json, text/csv
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

