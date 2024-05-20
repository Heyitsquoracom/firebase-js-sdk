Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# FunctionDeclaration interface
Structured representation of a function declaration as defined by the [OpenAPI 3.0 specification](https://spec.openapis.org/oas/v3.0.3)<!-- -->. Included in this declaration are the function name and parameters. This `FunctionDeclaration` is a representation of a block of code that can be used as a Tool by the model and executed by the client.

<b>Signature:</b>

```typescript
export declare interface FunctionDeclaration 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [description](./vertexai-preview.functiondeclaration.md#functiondeclarationdescription) | string | Optional. Description and purpose of the function. Model uses it to decide how and whether to call the function. |
|  [name](./vertexai-preview.functiondeclaration.md#functiondeclarationname) | string | The name of the function to call. Must start with a letter or an underscore. Must be a-z, A-Z, 0-9, or contain underscores and dashes, with a max length of 64. |
|  [parameters](./vertexai-preview.functiondeclaration.md#functiondeclarationparameters) | [FunctionDeclarationSchema](./vertexai-preview.functiondeclarationschema.md#functiondeclarationschema_interface) | Optional. Describes the parameters to this function in JSON Schema Object format. Reflects the Open API 3.03 Parameter Object. Parameter names are case sensitive. For a function with no parameters, this can be left unset. |

## FunctionDeclaration.description

Optional. Description and purpose of the function. Model uses it to decide how and whether to call the function.

<b>Signature:</b>

```typescript
description?: string;
```

## FunctionDeclaration.name

The name of the function to call. Must start with a letter or an underscore. Must be a-z, A-Z, 0-9, or contain underscores and dashes, with a max length of 64.

<b>Signature:</b>

```typescript
name: string;
```

## FunctionDeclaration.parameters

Optional. Describes the parameters to this function in JSON Schema Object format. Reflects the Open API 3.03 Parameter Object. Parameter names are case sensitive. For a function with no parameters, this can be left unset.

<b>Signature:</b>

```typescript
parameters?: FunctionDeclarationSchema;
```