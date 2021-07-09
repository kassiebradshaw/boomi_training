# FTP

*Notes taken*: 6-17-2021

## Objectives

* Locate FTP connector options
* Configure FTP Connector

---

FTP stands for **File Transfer Protocol**

To retrieve documents from FTP Server:

* Set up an FTP Connector
  * START SHAPE: Main component containing all information needed to connect to a single FTP Server
  * Combination of  parts:

    1. Connection (Where): FTP Server Hostname & user log-in
    2. Operation (How): Get or Send action, subdirectory and file filter definition

---

*Notes taken*: 7-8-2021

You can create a reusable FTP connection component using:

* **Host**: Host name, IP address, or Domain name of FTP Server
* **Port**: Listens for incoming client connections (default is 21)
* **Connection Mode**: Active or Passive (Passive is common for most setups)
* **User/Password**: Log-in info for account on FTP server

^ Remember this is a REUSABLE componenet. You can refer to it in other shapes instead of creating a new one.

### SSL Options

* **None / Explicit / Implicit**
  * used for invoking different types of client security

### FTP Operation: Configuration

*Options Tab*:

* **FTP Action**: Get/Get & Delete
* **Remote Directory**: Subdirectory the FTP user can access if deeper than the base directory
* **File Filter**: Conditionally reads files based on pattern matching
* **Transfer Type**: ASCII/Binary - Transfer files as text or as raw data
* **Max Files To Read**: Sets greatest number of files to read at once (Default for all files is "0")
