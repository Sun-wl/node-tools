# node-tools

## About
The tools for nodejs based application.

### Feature
* commone logger utilities.

## usage

`yarn add node-tools`

### Logger

Logger will provide stdout fro local dev and json format for fluentbit.
Logger 将在本地开发环境中提供标准输出（stdout），并为 Fluent Bit 提供 JSON 格式.

```javascript
const { logger } = require('node-tools')

logger.info('Hello world')
logger.error('error')
logger.debug('debug')
```