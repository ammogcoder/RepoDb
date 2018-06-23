## RepoDb

A dynamic ORM .Net Library used to create an entity-based repository classes when accessing data from the database.

### Package
Link: https://www.nuget.org/packages/RepoDb

### Documentation
Link: https://github.com/mikependon/RepoDb/blob/master/RepoDb.Documents/documentation_release_v1.md

### Goal

We aim to limit the implementation of SQL Statements in the .NET application.

### Vision

To provide more flexibility and fast-switching development approach, whether to use the massive or lightweight ORM operations.

### Principles

 - We will keep it simple as possible (KISS principle)
 - We will help developers to be more focus on SOLID principle
 - We will make it fast as possible
 - We will make it more flexible
 - We will never ever do try-catch inside the library
 - We will never make complex implementations (specially for complex Join Queries)

### What's with RepoDb?

 - Operations (Asynchronous)
 - Type Mapping
 - Field Mapping
 - Multiple Mapping
 - Expression Tree
 - Caching
 - Tracing
 - SQL Statement Builder
 - Transactions

### Operations

 - BatchQuery
 - BatchQueryAsync
 - Count
 - CountAsync
 - Query
 - QueryAsync
 - Insert
 - InsertAsync
 - Delete
 - DeleteAsync
 - DeleteAll
 - DeleteAllAsync
 - Update
 - UpdateAsync
 - InlineInsert
 - InlineInsertAsync
 - InlineMerge
 - InlineMergeAsync
 - InlineUpdate
 - InlineUpdateAsync
 - Merge
 - MergeAsync
 - BulkInsert
 - BulkInsertAsync
 - ExecuteReader
 - ExecuteReaderAsync
 - ExecuteQuery
 - ExecuteQueryAsync
 - ExecuteNonQuery
 - ExecuteNonQueryAsync
 - ExecuteScalar
 - ExecuteScalarAsync
