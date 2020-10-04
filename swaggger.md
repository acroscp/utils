[Editor](https://editor.swagger.io/)
server: swagger-ui(openapi 3.0+)

path option: `deprecate: true`

### Request

* header query path cookie 
* option
	* allowEmptyValue: true

[Variable Type](https://swagger.io/docs/specification/data-models/data-types/)

share
* nullable: true
* enum

unique
* string/format
    * work on input
	* binary (as file when ≥ openapi 3.0)
	* password(will let input hidden) 
    * work on response
	* date, date-time
        * ipv4,ipv6,uuid,hostname,email
    * not work
	* byte (base64)

option--input

* pattern
* minLength/maxLength

> number type: number, integer

format

* number: float, double
* integer: int32(=integer), int64(=long)

option

* minimum/maximun(+exclusive)
* mutipleOf

etc: boolean, null

array

items:
    type: vartype

### Option

* Complex: AllOf,AnyOf
