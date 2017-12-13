<!-- markdownlint-disable -->
# GenericMeasure

_QIX methods for version 12.101.0._

## `ApplyPatches`

Applies a patch to the properties of an object. Allows an update to some of the properties.<br>Applying a patch takes less time than resetting all the properties.

**Parameters:**

| Name | Type | Mandatory | Description |
| ---- | ---- | --------- | ----------- |
| `qPatches` | [`NxPatch`](./qix-engine-definitions.md#nxpatch) | Yes | Array of patches. |

_No return values._

## `GetInfo`

Returns the type and identifier of the object.

_No parameters._

**Returns:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `qInfo` | [`NxInfo`](./qix-engine-definitions.md#nxinfo) | `{"qId":"<identifier>","qType":"<type>"}` |

## `GetLayout`

Evaluates a measure and displays its properties, including the dynamic properties.

_No parameters._

**Returns:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `qLayout` | [`GenericMeasureLayout`](./qix-engine-definitions.md#genericmeasurelayout) | Information on the object. |

## `GetLinkedObjects`

Lists the linked objects to a generic object, a dimension or a measure.

_No parameters._

**Returns:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `qItems` | [`NxLinkedObjectInfo`](./qix-engine-definitions.md#nxlinkedobjectinfo) | List of the linked objects. |

## `GetMeasure`

Returns the definition of a measure.

_No parameters._

**Returns:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `qMeasure` | [`NxLibraryMeasureDef`](./qix-engine-definitions.md#nxlibrarymeasuredef) | Information about the measure. |

## `GetProperties`

Shows the properties of an object.<br>Returns the identifier and the definition of the measure.<br>If the member delta is set to true in the request object, only the delta is retrieved.<br>The following is always returned in the output:

_No parameters._

**Returns:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `qProp` | [`GenericMeasureProperties`](./qix-engine-definitions.md#genericmeasureproperties) | Information about the generic object. |

## `Publish`

Publishes a measure.

_No parameters._

_No return values._

## `SetProperties`

Sets some properties for a measure.

**Parameters:**

| Name | Type | Mandatory | Description |
| ---- | ---- | --------- | ----------- |
| `qProp` | [`GenericMeasureProperties`](./qix-engine-definitions.md#genericmeasureproperties) | Yes | Information about the measure. |

_No return values._

## `UnPublish`

Unpublishes a measure.

_No parameters._

_No return values._