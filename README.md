IDL - Schema
============

the syntax and metadata information for the IDL used between modules.
- it provides validation mechanisms, both at integrity level (checksum) and syntax level.
- definition of the BASE IDL format.
- it provides the parsing/generation of this IDL, by interfacing with some of the integrated adapters.

IDL - Adapters
==============
- it provides an adapter to serialize/deserialize the BASE IDL format.
- it provides an adapter to serialize/deserialize the MsgPack format.
- it provides an adapter to serialize/deserialize the JSON format.
- it provides an adapter to serialize/deserialize the BERT format.
- it provides an adapter to serialize/deserialize the Avro format.

IDL - Components
================
- Context
- DataObject
- Roles
- Algorithm
