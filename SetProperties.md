# Set Properties

*Notes taken*: 07-08-2021

## Objectives

* Define the Set Properties shape
* Use the Set Properties shape
* Set parameters

---

## What are Document Properties?

* It is possible to apply properties to a document throughout the process. By default docs are saved as a .DAT file with a filename equal to it's datetime stamp

* You must set destination document properties to rename the file

* Document Properties are configured using the Set Properties Shape
  * Extract runtime-related information related to a Document
  * Set new properties for destination Documents

## Set Properties Shape

* Acts as a 2-part container
  1. Properties to set - such as FTP file name
  2. Parameters - such as a static file name

## Setting Parameters

* Parameters can be a combination of static and dynamic
* It's a common interface for configuring dynamic runtime inputs
  * Reference elements from documents
  * Reference system date where the Process is executing
  * Define lookup inputs against databases and system APIs
  * Build dynamic messaging and notifications
