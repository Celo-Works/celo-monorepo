# Class: NameAccessor

## Hierarchy

* [SingleSchema](_identity_offchain_schema_utils_.singleschema.md)‹[NameType](../modules/_identity_offchain_schemas_.md#nametype)›

  ↳ **NameAccessor**

## Index

### Constructors

* [constructor](_identity_offchain_schemas_.nameaccessor.md#constructor)

### Properties

* [dataPath](_identity_offchain_schemas_.nameaccessor.md#datapath)
* [type](_identity_offchain_schemas_.nameaccessor.md#type)
* [wrapper](_identity_offchain_schemas_.nameaccessor.md#wrapper)

### Methods

* [read](_identity_offchain_schemas_.nameaccessor.md#read)
* [write](_identity_offchain_schemas_.nameaccessor.md#write)

## Constructors

###  constructor

\+ **new NameAccessor**(`wrapper`: [OffchainDataWrapper](_identity_offchain_data_wrapper_.offchaindatawrapper.md)): *[NameAccessor](_identity_offchain_schemas_.nameaccessor.md)*

*Overrides [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[constructor](_identity_offchain_schema_utils_.singleschema.md#constructor)*

*Defined in [contractkit/src/identity/offchain/schemas.ts:13](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schemas.ts#L13)*

**Parameters:**

Name | Type |
------ | ------ |
`wrapper` | [OffchainDataWrapper](_identity_offchain_data_wrapper_.offchaindatawrapper.md) |

**Returns:** *[NameAccessor](_identity_offchain_schemas_.nameaccessor.md)*

## Properties

###  dataPath

• **dataPath**: *string*

*Inherited from [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[dataPath](_identity_offchain_schema_utils_.singleschema.md#datapath)*

*Defined in [contractkit/src/identity/offchain/schema-utils.ts:10](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schema-utils.ts#L10)*

___

###  type

• **type**: *Type‹[NameType](../modules/_identity_offchain_schemas_.md#nametype)›*

*Inherited from [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[type](_identity_offchain_schema_utils_.singleschema.md#type)*

*Defined in [contractkit/src/identity/offchain/schema-utils.ts:9](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schema-utils.ts#L9)*

___

###  wrapper

• **wrapper**: *[OffchainDataWrapper](_identity_offchain_data_wrapper_.offchaindatawrapper.md)*

*Overrides [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[wrapper](_identity_offchain_schema_utils_.singleschema.md#wrapper)*

*Defined in [contractkit/src/identity/offchain/schemas.ts:14](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schemas.ts#L14)*

## Methods

###  read

▸ **read**(`account`: string): *Promise‹undefined | T›*

*Inherited from [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[read](_identity_offchain_schema_utils_.singleschema.md#read)*

*Defined in [contractkit/src/identity/offchain/schema-utils.ts:13](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schema-utils.ts#L13)*

**Parameters:**

Name | Type |
------ | ------ |
`account` | string |

**Returns:** *Promise‹undefined | T›*

___

###  write

▸ **write**(`data`: [NameType](../modules/_identity_offchain_schemas_.md#nametype)): *Promise‹void›*

*Inherited from [SingleSchema](_identity_offchain_schema_utils_.singleschema.md).[write](_identity_offchain_schema_utils_.singleschema.md#write)*

*Defined in [contractkit/src/identity/offchain/schema-utils.ts:17](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/identity/offchain/schema-utils.ts#L17)*

**Parameters:**

Name | Type |
------ | ------ |
`data` | [NameType](../modules/_identity_offchain_schemas_.md#nametype) |

**Returns:** *Promise‹void›*
