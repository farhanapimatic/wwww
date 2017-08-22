# 

this is one of the things we are working on it.



## Base URL

The Base URL for this API is `http://Example.org/ICalculator`









# <a name="api_reference"></a>API Reference

* [DefaultBinding_ICalculator](#default_binding_i_calculator)

## <a name="default_binding_i_calculator"></a>![Endpoint Group: ](https://apidocs.io/img/class.png "DefaultBinding_ICalculator") DefaultBinding_ICalculator


### <a name="add"></a>![Endpoint: ](https://apidocs.io/img/method.png "Add") Add


**`POST`** `/AdD`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ICalculator_Add_InputMessage](#i_calculator_add_input_message) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "parameters": {
    "a": 231,
    "b": 231
  }
}
``` 

#### Responses
**200** 


Body ([ICalculator_Add_OutputMessage](#i_calculator_add_output_message)) 
```
{
  "parameters": {
    "result": 231
  }
}
```


### <a name="subtract"></a>![Endpoint: ](https://apidocs.io/img/method.png "Subtract") Subtract


**`POST`** `/Subtract`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ICalculator_Subtract_InputMessage](#i_calculator_subtract_input_message) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "parameters": {
    "a": 231,
    "b": 231
  }
}
``` 

#### Responses
**200** 


Body ([ICalculator_Subtract_OutputMessage](#i_calculator_subtract_output_message)) 
```
{
  "parameters": {
    "result": 231
  }
}
```


[Back to API Reference](#api_reference)

## <a name="api_types"></a>![Models: ](https://apidocs.io/img/class.png "API Types") API Types

This section provides details on the available types. The primitive types available are:

| Type | Example |
| ---- | -------- |
| **string** | `hello world` |
| **boolean** |	`true` |
| **number** | `1` |
| **precision** | `1.5` |
| **datetime** | `2016-03-13T12:52:32.123Z` |
| **date** | `2016-03-13` |
|**void** | |
| **dynamic** | |
| **binary** | |
| **long** | `12345678910` |
| **file** | |
| **uuid** | `0f8fad5b-d9cb-469f-a165-70867728950e` |


In addition to the above types, the following complex types are also available:
### <a name="add"></a>![Model: ](https://apidocs.io/img/method.png "Add") Add



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| a | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| b | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="add_response"></a>![Model: ](https://apidocs.io/img/method.png "AddResponse") AddResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| result | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="subtract"></a>![Model: ](https://apidocs.io/img/method.png "Subtract") Subtract



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| a | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| b | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="subtract_response"></a>![Model: ](https://apidocs.io/img/method.png "SubtractResponse") SubtractResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| result | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="i_calculator_add_output_message"></a>![Model: ](https://apidocs.io/img/method.png "ICalculator_Add_OutputMessage") ICalculator_Add_OutputMessage



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| parameters | [AddResponse](#add_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="i_calculator_subtract_output_message"></a>![Model: ](https://apidocs.io/img/method.png "ICalculator_Subtract_OutputMessage") ICalculator_Subtract_OutputMessage



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| parameters | [SubtractResponse](#subtract_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="i_calculator_add_input_message"></a>![Model: ](https://apidocs.io/img/method.png "ICalculator_Add_InputMessage") ICalculator_Add_InputMessage



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| parameters | [Add](#add) |  ``` Required ```  | TODO: Add a property description | 




### <a name="i_calculator_subtract_input_message"></a>![Model: ](https://apidocs.io/img/method.png "ICalculator_Subtract_InputMessage") ICalculator_Subtract_InputMessage



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| parameters | [Subtract](#subtract) |  ``` Required ```  | TODO: Add a property description |

