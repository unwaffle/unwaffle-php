# Swagger\Client\LabelApi

All URIs are relative to *https://api.unwaffle.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addLabel**](LabelApi.md#addLabel) | **POST** /label | Add or update a Label


# **addLabel**
> addLabel($body)

Add or update a Label



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure HTTP basic authorization: basicAuth
Swagger\Client\Configuration::getDefaultConfiguration()->setUsername('YOUR_USERNAME');
Swagger\Client\Configuration::getDefaultConfiguration()->setPassword('YOUR_PASSWORD');

$api_instance = new Swagger\Client\Api\LabelApi();
$body = new \Swagger\Client\Model\Label(); // \Swagger\Client\Model\Label | A Label object. The API will also happily consume a CSV or TSV with one record per line and no header row.

try {
    $api_instance->addLabel($body);
} catch (Exception $e) {
    echo 'Exception when calling LabelApi->addLabel: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Swagger\Client\Model\Label**](../Model/\Swagger\Client\Model\Label.md)| A Label object. The API will also happily consume a CSV or TSV with one record per line and no header row. | [optional]

### Return type

void (empty response body)

### Authorization

[basicAuth](../../README.md#basicAuth)

### HTTP request headers

 - **Content-Type**: application/json, text/csv
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

