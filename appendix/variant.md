## Properties of &lt;variant&gt; Field
The **&lt;variant&gt;** field has all the [common](fields.md) properties as
well as ones listed below. Refer to [&lt;variant&gt; Field](../fields/variant.md) chapter
for detailed description. 

|Property Name|Allowed type / value|DSL Version|Required|Default Value|Description|
|:-----------:|:------------------:|:---------:|:------:|:-----------:|-----------|
|**defaultMember**|[name](../intro/names.md) or [numeric](../intro/numeric.md) index|1|no|-1|Default member. Negative number means no member selected.|
|**displayIdxReadOnlyHidden**|[bool](../intro/boolean.md)|1|no|false|Hide active index of the member when field displayed in read-only mode.|


The **&lt;variant&gt;** field also allows listing of member fields using
**&lt;members&gt;** child XML element.
