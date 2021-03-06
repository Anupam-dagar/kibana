<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [Plugin](./kibana-plugin-server.plugin.md)

## Plugin interface

The interface that should be returned by a `PluginInitializer`<!-- -->.

<b>Signature:</b>

```typescript
export interface Plugin<TSetup, TStart, TPluginsSetup extends Record<PluginName, unknown> = {}, TPluginsStart extends Record<PluginName, unknown> = {}> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [setup](./kibana-plugin-server.plugin.setup.md) | <code>(core: CoreSetup, plugins: TPluginsSetup) =&gt; TSetup &#124; Promise&lt;TSetup&gt;</code> |  |
|  [start](./kibana-plugin-server.plugin.start.md) | <code>(core: CoreStart, plugins: TPluginsStart) =&gt; TStart &#124; Promise&lt;TStart&gt;</code> |  |
|  [stop](./kibana-plugin-server.plugin.stop.md) | <code>() =&gt; void</code> |  |

