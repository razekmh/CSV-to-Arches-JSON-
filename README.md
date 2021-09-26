<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** razekmh, CSV-to-Arches-JSON, data_champ, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

<!-- PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/razekmh/CSV-to-Arches-JSON">
    <img src="images/logo.png" alt="Logo" width="%80" height="%80">
  </a>

  <h3 align="center">CSV-to-Arches-JSON</h3>

  <p align="center">
    Converts CSV files to JSON files readable by Arches system
    <br />
    <a href="https://github.com/razekmh/CSV-to-Arches-JSON"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/razekmh/CSV-to-Arches-JSON/issues">Report Bug</a>
    ·
    <a href="https://github.com/razekmh/CSV-to-Arches-JSON/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This will be a utility to transform CSV of a specified format to JSON format readable by Arches.

_"[Arches](https://arches.readthedocs.io/en/latest/) is a web-based, geospatial information system for cultural heritage inventory and management. The platform is purpose-built for the international cultural heritage field, and it is designed to record all types of immovable heritage, including archaeological sites, buildings and other historic structures, landscapes, and heritage ensembles or districts."_

Data input to Arches can be achieved using a dedicated GUI or an API. Bulk data upload is only possible using the API. [Arches API accepts data in three formats](https://arches.readthedocs.io/en/latest/import-export/); JSON, CSV and shapefiles. Each of the formats require a dedicated structure. 

Arches main data structure is based on [resource models](https://arches.readthedocs.io/en/latest/data-model/#resource-model-overview). A resource model must be created before its data is added to the system. Multiple resource models can be created for any project and relationships between them can be established. 

Assuming that you are using the API to input data to Arches, you will need a mapping file for each resource model. You can download the mapping file from the _Arches designer_ page. A mapping file for _Example resource file_ looks like this.
```JSON
{
    "resource_model_id": "f2a47ff0-c4cb-4914-9e19-da7142eaf29d",
    "resource_model_name": "Example Resource Model",
    "nodes": [
        {
            "arches_nodeid": "205ee073-1d93-4119-ad5f-8b830be005aa",
            "arches_node_name": "Name",
            "file_field_name": "",
            "data_type": "string",
            "export": true
        },
        {
            "arches_nodeid": "b69e5110-95f2-46dc-8243-6b1297cf969e",
            "arches_node_name": "Active",
            "file_field_name": "",
            "data_type": "boolean",
            "export": true
        },
        {
            "arches_nodeid": "54e8646e-dd42-4c52-a392-3eeb2d6f6345",
            "arches_node_name": "Type",
            "file_field_name": "",
            "data_type": "concept",
            "concept_export_value": "label",
            "export": true
        }
    ]
}
```
 



### Built With

* []()
* []()
* []()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/razekmh/CSV-to-Arches-JSON.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/razekmh/CSV-to-Arches-JSON/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Mahmoud Abdelrazek - [@data_champ](https://twitter.com/data_champ)

Project Link: [https://github.com/razekmh/CSV-to-Arches-JSON](https://github.com/razekmh/CSV-to-Arches-JSON)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/razekmh/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/razekmh/CSV-to-Arches-JSON/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/razekmh/repo.svg?style=for-the-badge
[forks-url]: https://github.com/razekmh/CSV-to-Arches-JSON/network/members
[stars-shield]: https://img.shields.io/github/stars/razekmh/repo.svg?style=for-the-badge
[stars-url]: https://github.com/razekmh/CSV-to-Arches-JSON/stargazers
[issues-shield]: https://img.shields.io/github/issues/razekmh/repo.svg?style=for-the-badge
[issues-url]: https://github.com/razekmh/CSV-to-Arches-JSON/issues
[license-shield]: https://img.shields.io/github/license/razekmh/repo.svg?style=for-the-badge
[license-url]: https://github.com/razekmh/CSV-to-Arches-JSON/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/razekmh
