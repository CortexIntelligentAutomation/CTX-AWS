<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-AWS
Cortex Subtasks which interact with Amazon Web Services (AWS) without using the AWS Graphical User Interface.

The module allows users to perform the following functionality:
* EC2 Virtual Machines
	* Create New VM
	* Start VM
	* Restart VM
	* Deallocate VM
	* Terminate VM
	* Get VM
*  IAM
	* Get User Information
* Usage
	* Get Daily/Monthly Billing Information
* Alarm
	* Create CPU Alarm for Instance

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-AWS module was developed in Cortex v6.3.0. Some functionality may not be available in other verions of Cortex.

### OCIs
The CTX-AWS module requires the following Cortex OCIs:
* PowerShell

### Files
The CTX-AWS module requires the following files:
* [CTX-AWS Studio Package](https://github.com/CortexIATest/CTXExcel/releases/download/untagged-735f460df6f7d65c9d19/Cortex.Studio.Package.-.V2.2.studiopkg)

### Other Requisites
The CTX-AWS module has the following additional requirements which are explained in detail in the [Deployment Plan](#Installation):
* To use the AWS Tools for Windows PowerShell or the AWS Tools for PowerShell Core, you must have an
AWS account.
* PowerShell v5 to be installed on the application server
* AWSPowerShell module installed

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](#Installation).

## How to use
A detailed User Guide has been provided with instructions on how to use the flows/subtasks, available [here](https://github.com/CortexIATest/CTXExcel/blob/master/CTXExcel%20-%20LLD%20-%20v2.2.docx). Configuration of subtask inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-AWS module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.1 | 25/09/2018 | Get Users | Created
v1.1 | 25/09/2018 | Get Cost | Created
v1.0 | 12/05/2017 | Create CPU Alarm For Instance | Created
v1.0 | 12/05/2017 | Change Instance | Created
v1.0 | 12/05/2017 | Terminate Instance | Created
v1.0 | 12/05/2017 | Restart Instance | Created
v1.0 | 12/05/2017 | Stop Instance | Created
v1.0 | 12/05/2017 | Start Instance | Created
v1.0 | 12/05/2017 | Get Instance | Created
v1.0 | 12/05/2017 | Create Instance | Created

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
