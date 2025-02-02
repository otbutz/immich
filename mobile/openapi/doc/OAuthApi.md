# openapi.api.OAuthApi

## Load the API package
```dart
import 'package:openapi/api.dart';
```

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**callback**](OAuthApi.md#callback) | **POST** /oauth/callback | 
[**generateConfig**](OAuthApi.md#generateconfig) | **POST** /oauth/config | 
[**link**](OAuthApi.md#link) | **POST** /oauth/link | 
[**unlink**](OAuthApi.md#unlink) | **POST** /oauth/unlink | 


# **callback**
> LoginResponseDto callback(oAuthCallbackDto)



### Example
```dart
import 'package:openapi/api.dart';

final api_instance = OAuthApi();
final oAuthCallbackDto = OAuthCallbackDto(); // OAuthCallbackDto | 

try {
    final result = api_instance.callback(oAuthCallbackDto);
    print(result);
} catch (e) {
    print('Exception when calling OAuthApi->callback: $e\n');
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oAuthCallbackDto** | [**OAuthCallbackDto**](OAuthCallbackDto.md)|  | 

### Return type

[**LoginResponseDto**](LoginResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **generateConfig**
> OAuthConfigResponseDto generateConfig(oAuthConfigDto)



### Example
```dart
import 'package:openapi/api.dart';

final api_instance = OAuthApi();
final oAuthConfigDto = OAuthConfigDto(); // OAuthConfigDto | 

try {
    final result = api_instance.generateConfig(oAuthConfigDto);
    print(result);
} catch (e) {
    print('Exception when calling OAuthApi->generateConfig: $e\n');
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oAuthConfigDto** | [**OAuthConfigDto**](OAuthConfigDto.md)|  | 

### Return type

[**OAuthConfigResponseDto**](OAuthConfigResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **link**
> UserResponseDto link(oAuthCallbackDto)



### Example
```dart
import 'package:openapi/api.dart';

final api_instance = OAuthApi();
final oAuthCallbackDto = OAuthCallbackDto(); // OAuthCallbackDto | 

try {
    final result = api_instance.link(oAuthCallbackDto);
    print(result);
} catch (e) {
    print('Exception when calling OAuthApi->link: $e\n');
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oAuthCallbackDto** | [**OAuthCallbackDto**](OAuthCallbackDto.md)|  | 

### Return type

[**UserResponseDto**](UserResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **unlink**
> UserResponseDto unlink()



### Example
```dart
import 'package:openapi/api.dart';

final api_instance = OAuthApi();

try {
    final result = api_instance.unlink();
    print(result);
} catch (e) {
    print('Exception when calling OAuthApi->unlink: $e\n');
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**UserResponseDto**](UserResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

