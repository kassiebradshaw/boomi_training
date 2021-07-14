# Branch Shape

*Notes Taken*: 07-14-2021

## Objectives

* Explain how to use the branch shape

---

* We want to create 2 files:
  * XML for archiving
  * CSV (flat file) for reporting

* We want to apply multiple operations to a document or a set of documents to serve different purposes.
  * For this, we use a branch shape

## What is a Branch?

* Creates a copy of the document(s) and executes each path in sequential order.
* A Branch's path is executed to completion before flowing to the next branch.
* Documents only flow down subsequent paths when/if it successfully completes the preceding path
* A given Branch shape can have up to 25 paths (but what's commonly used is between 2 & 6)
