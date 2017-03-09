# Swagger\Client\ParticipantApi

All URIs are relative to *https://api.unwaffle.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addParticipant**](ParticipantApi.md#addParticipant) | **POST** /participant | Add or update a Participant


# **addParticipant**
> addParticipant($body)

Add or update a Participant



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure HTTP basic authorization: basicAuth
Swagger\Client\Configuration::getDefaultConfiguration()->setUsername('YOUR_USERNAME');
Swagger\Client\Configuration::getDefaultConfiguration()->setPassword('YOUR_PASSWORD');

$api_instance = new Swagger\Client\Api\ParticipantApi();
$body = new \Swagger\Client\Model\Participant(); // \Swagger\Client\Model\Participant | A Participant object. The API will also happily consume a CSV or TSV with one record per line and no header row.

try {
    $api_instance->addParticipant($body);
} catch (Exception $e) {
    echo 'Exception when calling ParticipantApi->addParticipant: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Swagger\Client\Model\Participant**](../Model/\Swagger\Client\Model\Participant.md)| A Participant object. The API will also happily consume a CSV or TSV with one record per line and no header row. | [optional]

### Return type

void (empty response body)

### Authorization

[basicAuth](../../README.md#basicAuth)

### HTTP request headers

 - **Content-Type**: application/json, text/csv
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

