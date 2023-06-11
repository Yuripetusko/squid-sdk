# Change Log - @subsquid/evm-processor

This log was last generated on Sun, 11 Jun 2023 15:49:45 GMT and should not be manually modified.

## 1.3.0
Sun, 11 Jun 2023 15:49:45 GMT

### Minor changes

- add `.rateLimit` option to RPC connection settings
- downgrade `TypeScript` to `4.9.5`

### Patches

- fix: `eth_getBlockReceipts` doesn't accept block hash on some endpoints
- catch `Expect block number from id` as concisitency error

## 1.2.0
Sat, 10 Jun 2023 15:11:08 GMT

### Minor changes

- optimise cost of RPC ingestion by better selection of used methods
- always use debug_traceBlockByHash to fetch state diffs of non-finalized blocks to guarantee data consistency
- rename `EvmBatchProcessor.useTraceApi()` to `EvmBatchProcessor.preferTraceApi()`
- add `TraceRequest.parents` option
- migrate to TypeScript 5 and update other dependencies

## 1.1.0
Mon, 05 Jun 2023 09:30:42 GMT

### Minor changes

- adapt for new processor tools

## 1.0.1
Mon, 08 May 2023 12:14:55 GMT

### Patches

- not all transaction fields where passed to the data handler

## 1.0.0
Mon, 01 May 2023 18:57:46 GMT

### Breaking changes

- Introduce ArrowSquid
