---
title: "{asset}"
layout: docs
categories: ["Theming", "Smarty"]
---

## Function: `{asset}`

```
{asset name="string" id="string" tag="string" class="string"}
```

Renders an asset from the controller.

### Parameters

Parameter   | Type      | Default   | Description
---         | ---       | ---       | ---
__`name`__  | `string`  | none      | The name of the asset
`id`        | `string`  | `$name`   | The id of the tag if different than the name
`tag`       | `string`  | none      | The type of tag to wrap the asset in
`class`     | `string`  | none      | The class to add to the asset wrapper
