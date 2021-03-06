---
title: "Update configuration"
aliases:
  - pybytes/api/update_config
---

  Update device configuration parameters.

**Method**
----
**pybytes.update_config(key, value, permanent, silent, reconnect)**

**Parameters**
----
| name  | Description   | is Required    | Default value
| ------------- |:-------------:|:-------------:|:-------------:|
| key   | key  | Yes   | None |
| value   | value  | No   | None |
| permanent   | boolean  | No   | True |
| silent   | boolean  | No   | False |
| reconnect   | boolean  | No   | False |

**Example**
----
`pybytes.update_config(key="wifi", value={'password': 'Pa$$w0rd'}, permanent=True, silent=False, reconnect=False)`

**Success Response**
----

Pybytes configuration written to /flash/pybytes_config.json
