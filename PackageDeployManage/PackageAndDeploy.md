# Package Components and Deploy

*Notes Taken*: 07-14-2021

## Objectives

* Create Packaged Components
* Deploy a Process

---

## Packaged Components Workflow

* Build
  * Design and build integrations using a visual tool which includes access to a library of prebuilt connectors
* Package Components
  * Package the component from the Build page or Deploy Menu
* Deploy Components
  * Deploy packaged components to environments from the Deploy Menu
* Manage
  * This unique architecture enables centralized management of all integrations from the platform

## Deploy vs. Execute

* Deploying a Process does **NOT** Execute the Process into active production
* Once a Process is Deployed, it needs to be Executed either by:
  * Manual execution (Manage -> Process Reporting)
  * Applying a schedule (Manage -> Atom Management)
  * External event triggering a Listener process
