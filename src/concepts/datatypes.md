# Datatypes

Throughout the DataJoint ecosystem, there are several datatypes that are used to define tables with cross-platform support i.e. Python, MATLAB. It is important to understand these types as they can have implications in the queries you form and the capacity of their storage.

## Standard Types

These types are largely wrappers around existing types in MySQL since this is the backend to the DataJoint Engine.

| Datatype | Description | Size | Example |
| --- | --- | ---| --- |
| int | integer | 4 bytes | `8` |

## Unique Types

| Datatype | Description | Size | Example |
| --- | --- | ---| --- |
| uuid | a unique GUID value | 16 bytes | `6ed5ed09-e69c-466f-8d06-a5afbf273e61` |