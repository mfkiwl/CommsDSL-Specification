## Properties of &lt;value&gt; Layer
The **&lt;value&gt;** layer has all the [common](layers.md) properties as
well as ones listed below. Refer to [&lt;value&gt; Layer](../frames/value.md) chapter
for detailed description. 

|Property Name|Allowed type / value|DSL Version|Required|Default Value|Description|
|:-----------:|:------------------:|:---------:|:------:|:-----------:|-----------|
|**interfaces**|comma separated list of [names](../intro/names.md)|1|no||List of supported [&lt;interfaces&gt;](../interfaces/interfaces.md).|
|**interfaceFieldName**|[name](../intro/names.md) string|1|yes (only if **interfaces** is not empty)||Name of the relevant field inside each [&lt;interface&gt;](../interfaces/interfaces.md).|
|**pseudo**|[bool](../intro/boolean.md)|1|no|false|Mark the layer as **pseudo** one, i.e. one that doesn't serialize its field.|
