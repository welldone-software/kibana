<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-data-server](./kibana-plugin-plugins-data-server.md) &gt; [ISearchOptions](./kibana-plugin-plugins-data-server.isearchoptions.md)

## ISearchOptions interface

<b>Signature:</b>

```typescript
export interface ISearchOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [abortSignal](./kibana-plugin-plugins-data-server.isearchoptions.abortsignal.md) | <code>AbortSignal</code> | An <code>AbortSignal</code> that allows the caller of <code>search</code> to abort a search request. |
|  [isRestore](./kibana-plugin-plugins-data-server.isearchoptions.isrestore.md) | <code>boolean</code> | Whether the session is restored (i.e. search requests should re-use the stored search IDs, rather than starting from scratch) |
|  [isStored](./kibana-plugin-plugins-data-server.isearchoptions.isstored.md) | <code>boolean</code> | Whether the session is already saved (i.e. sent to background) |
|  [sessionId](./kibana-plugin-plugins-data-server.isearchoptions.sessionid.md) | <code>string</code> | A session ID, grouping multiple search requests into a single session. |
|  [strategy](./kibana-plugin-plugins-data-server.isearchoptions.strategy.md) | <code>string</code> | Use this option to force using a specific server side search strategy. Leave empty to use the default strategy. |

