# Document Flow Process

*Notes taken*: 07-08-2021

## Objectives

* Define a document
* Understand document flow

---

## What is a Document?

The document powers the execution in a process flow

* Boomi supports **five** raw document types:
  * XML
  * JSON
  * Flat File
  * Database
  * EDI

* Documents are presented in **four** different formats:
  * **Records** - for Flat File and Database
  * **Transactions** - for XML and EDI
  * **File Instances** - for any communication between systems not needing a structure analysis
    * Examples: email attachments or export to disk
  * **Empty** - for simple triggering of later shapes in a process

## Document Flow

* Documents often represent individual files brought into the process.
* A single document may contain many records. If this is the case:
  * Use the Data Process shape to split a document so each has a single record for processing
    * Useful for handling a large daily batch of process orders, splitting each order into many documents

EXAMPLES:

* **Start -> Map -> Data Process -> Set Properties ->Written To Disk**

* **Start -> Decision Shape (True or False Path)**
