# helper-functions for Tenant App
This package helps to make two set of functions available globally in tenantApp

## Installation
To install, use the command below<br>
`code` npm install tenantapp-helper-functions

## Usage
### How to require the 2 functions.
`code` const { isValidMongooseId } = require('tenantapp-helper-functions');<br>
`code` const { schemaError} = require('tenantapp-helper-functions');;

### The isValidMongooseId function usage
`code` isvalidMongooseId('pass in the mongoose Id');<br><br>

### The schemaError function usage
`code` schema('pass in the model');<br><br>