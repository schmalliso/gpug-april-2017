# CRUD

## Write Operations

### Create Operations

Create (or "insert") operations add new [documents](#document) to a [collection](#collections). If
the collection does not currently exist, insert operations will create
the collection.

MongoDB provides the following methods to insert documents into a collection:

- db.collection.insertOne() New in version 3.2
- db.collection.insertMany() New in version 3.2

In MongoDB, insert operations target a single collection. All write
operations in MongoDB are atomic on the level of a single document.

[etc…]

## Glossary

### Document

A record in a MongoDB [collection](#collection) and the basic unit of data in MongoDB. Documents are analogous to JSON objects but exist in the database in a more type-rich format known as [BSON](#bson). etc.

### Collection

A grouping of MongoDB [documents](#document). A collection is the equivalent of an RDBMS table. A collection exists within a single database. Collections do not enforce a schema. Documents within a collection can have different fields. etc…
