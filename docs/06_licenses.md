# Licenses
This section provides a recommendation on how to communicate software or document licenses information in a project.

## Software Code Licenses

Ideally, the project SHOULD communicate software license information via three different methods:

* In the README file
* Inside of the repository with a ```License.txt``` document
* Inside of each code file created by the group.

### Statement in README File
Insert in the README file one of these statements (depending on the license type):

The README file will display one of these three licenses:

* ![APM license](https://img.shields.io/badge/License-MIT-brightgreen)

* ![APM license](https://img.shields.io/badge/License-Apache_2.0-brightgreen) 

* ![APM license](https://img.shields.io/badge/License-Mozilla_Public_License_2.0-brightgreen) 

Also, it is recommended to include a plain text statement of the license in the README file, for accessibility purposes as well as enabling parsing by automated tooling. This can be done by including a "License" section with one of the following, as appropriate:

* This project is licensed under the [MIT license](https://github.com/volumetricformat/Templates/blob/main/License/MIT.txt).

* This project is licensed under the [Apache-2.0 license](https://github.com/volumetricformat/Templates/blob/main/License/Apache-2_0.txt).

* This project is licensed under the Mozilla Public License, version 2.0 [MPL-2.0](https://github.com/volumetricformat/Templates/blob/main/License/Mozilla-v2_0.txt).

### License File in the Repository
Insert in the repository a file called ```License.txt```. 

The Maintainer or Chair can copy the corresponding license file from the [templates/license](https://github.com/volumetricformat/Templates/tree/main/License) repository and upload it to the project repository.


### License Reference in each Source Code File
The recommendation is that projects SHOULD use [SPDX short-form license identifiers](https://spdx.dev/ids/) in all source code and documentation files that are **original to the project**.


Each source code created by the project SHOULD have one of these SPDX license identifiers: (depending on the type of source code license allocated to the project)

* **for an MIT license:**

```
# SPDX-License-Identifier: MIT
# Copyright Contributors to the Volumetric Format Association
```

* **for a Apache 2.0 license:**

```
# SPDX-License-Identifier: Apache-2.0
# Copyright Contributors to the Volumetric Format Association
```

* **for a Mozilla Public License 2.0 license:**

```
# SPDX-License-Identifier: MPL-2.0
# Copyright Contributors to the Volumetric Format Association
```

If the project needs to include source code or documents from a different upstream project, the recommendation is to retain those files in **unmodified form** _**(don't add identifiers)**_.

Also consider to:

* keep these files in sync with the upstream project
* ask the upstream project to insert the identifiers on their source code files/documents.

# Technical Document License
```
Note: Details to be added/updated after VFA Charter has been Approved
```
In projects where the main deliverables are technical documents, each document MUST have a [VFA legal disclaimer](https://github.com/volumetricformat/the_way_we_work/blob/Initial_proposal/Support_Documentation/License/VFA_License.txt) inserted.
