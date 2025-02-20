<!-- NOTE: THIS FILE IS AUTOGENERATED. DO NOT EDIT BY HAND. -->
<!-- see templates/registry/markdown/attribute_namespace.md.j2 -->

# Oracle Database

## Oracle Database Attributes

This section defines attributes for Oracle Database.

| Attribute | Type | Description | Examples | Stability |
|---|---|---|---|---|
| <a id="oracledb-pool-min" href="#oracledb-pool-min">`oracledb.pool.min`</a> | int | This read-only property is a number which specifies the minimum number of connections a connection pool maintains, even when there is no activity to the target database. | `0`; `3`; `4` | ![Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-pool-max" href="#oracledb-pool-min">`oracledb.pool.max`</a> | int | This read-only property is a number which specifies the maximum number of connections that can be open in the connection pool. | `2`; `30`; `70` | ![Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-pool-incr" href="#oracledb-pool-min">`oracledb.pool.incr`</a> | int | This read-only property is a number which specifies the number of connections that are opened whenever a connection request exceeds the number of currently open connections. | `2`; `10`; `15` | ![Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-bind-values" href="#oracledb-bind-values">`oracledb.bind.values`</a> | string[] | Array of bind values passed to parameterized queries. | `['43', 'scott', 'true'` | [Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-instance" href="#oracledb-instance">`oracledb.instance`</a> | string | Oracle Database Instance. | `ORCL1`; `ORCL2`; | [Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-pdbname" href="#oracledb-pdbname">`oracledb.pdbname`</a> | string | Pluggable Database (PDB) name in a Multitenant Container Database (CDB) environment. | `PDB1`; `PDB2`; | [Development](https://img.shields.io/badge/-development-blue) |
| <a id="oracledb-implicit_release" href="#oracledb-implicit_release">`oracledb.implicit_release`</a> | boolean | Indicates if the internal connection is released back to pool or not after executing a query. | `true` | [Development](https://img.shields.io/badge/-development-blue) |

---
