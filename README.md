# Library Simplified Data Store

This is the Data Store for [Library Simplified](http://www.librarysimplified.org/). The data store contains information from a variety of sources, supporting the accurate classification and thorough metadata of book records.

The [Metadata Wrangler](https://github.com/NYPL-Simplified/metadata-wrangler) depends on the data store for its installation.

## Installation & Workflow

Thorough deployment instructions, including essential libraries for Linux systems, can be found [in the Library Simplified wiki](https://github.com/NYPL-Simplified/Simplified-iOS/wiki/Deployment-Instructions). **_If this is your first time installing a Library Simplified repository, please review those instructions._**

Should you need to work on the data store, use a traditional git workflow:
```sh
$ git clone git@github.com:NYPL-Simplified/data.git data
```

If you are using the data store in conjunction with the Metadata Wrangler, be sure to include its full local path as the value of the "data_directory" property in your metadata configuration json file.

## License

The Library Simplified Data Store contains information from [FAST (Faceted Application of Subject Terminology)](http://www.oclc.org/research/themes/data-science/fast/download.html) Data which is made available by OCLC Online Computer Library Center, Inc. under the [ODC Attribution License](http://www.oclc.org/research/themes/data-science/fast/odcby.html).

The [Library of Congress Subject Headings](http://id.loc.gov/authorities/subjects.html) included in LS Data Store are part of a public domain data set made available by the [Library of Congress Linked Data Service](http://id.loc.gov/about/).

Finally, the appeals data included is made available under the Apache License, as detailed below.

    Copyright © 2015 The New York Public Library, Astor, Lenox, and Tilden Foundations

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express
    or implied. See the License for the specific language governing
    permissions and limitations under the License.
