<!--# SAP-samples/repository-template
This default template for SAP Samples repositories includes files for README, LICENSE, and .reuse/dep5. All repositories on github.com/SAP-samples will be created based on this template.

# Containing Files

1. The LICENSE file:
In most cases, the license for SAP sample projects is `Apache 2.0`.

2. The .reuse/dep5 file: 
The [Reuse Tool](https://reuse.software/) must be used for your samples project. You can find the .reuse/dep5 in the project initial. Please replace the parts inside the single angle quotation marks < > by the specific information for your repository.

3. The README.md file (this file):
Please edit this file as it is the primary description file for your project. You can find some placeholder titles for sections below. -->

# SAP Concur Web Services - Updating Expense Reports and Entries
<!-- Please include descriptive title -->

<!--- Register repository https://api.reuse.software/register, then add REUSE badge:
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/REPO-NAME)](https://api.reuse.software/info/github.com/SAP-samples/REPO-NAME)
-->

## Description
This collection provides examples for updating Concur expense report and expense entry data using Concur's Expense API offerings. The following scenarios are included in the Updating Expense Reports and Entries.postman_collection.json:

1.Retrieving header data for all expense reports

2.Retrieving expense report header data for a specific ReportID

3.Retrieving expense entries for a specific ReportID

4.Retrieving expense entry data for a specific Expense ID

5.Updating expense report header data

    1.Retrieve Unique User ID
    
    2.Update Header Text Field
    
    3.Update Header Connect List Fields
    
6.How to update expense report entry fields

For an understanding on how to use this repository, read the following blog post (to be linked)


## Requirements
In order to use this repository you will need

1.The Web Service Administration role within SAP Concur (to be able to create SAP Concur applications)


2.Postman (to be able to use the files included in this repository)


## Download and Installation

## Known Issues
No known issues.

## How to obtain support
This project is provided "as-is", with no expected changes or support. The complete authentication documentation [can be found here](https://developer.concur.com/api-reference/expense/expense-report/v4.expenses.html).
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing
This repository is provided "as-is".

## License
Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
