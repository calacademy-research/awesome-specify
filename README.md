<p align="center">
  <br>
  <img width="400" src="https://github.com/user-attachments/assets/fddc33e2-1d0b-486f-9482-d077068e9f66" alt="logo of vue-awesome repository">
  <br>
  <br>
</p>

# Awesome Specify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A community-driven list of Specify integrations, software, and resources developed by the community.

## Contents

- [Specify Software](#specify)
- [Taxonomy](#taxonomy)
- [Software Testing](#testing)
- [Miscellaneous](#miscellaneous)

## Specify

This covers the major software offerings of the Specify Collections Consortium.

-  **[Specify 7](https://github.com/specify/specify7)**: Specify's flagship web-based platform for managing biological and geological collections data.
-  **[Specify 6](https://github.com/specify/specify6) [Deprecated]**: Java-based desktop application for managing biological collections. Superseded by Specify 7.
-  **[Specify Web Asset Server](https://github.com/specify/web-asset-server)**: A Specify accessory program that facilitates the storage, management, and delivery of digital assets.
-  **[Specify Report Runner](https://github.com/specify/report-runner-service)**: A simple web service wrapper around the Jasper Reports libraries for report and label generation in Specify 7.
-  **[Specify Docker Compositions](https://github.com/specify/docker-compositions)**: A private repository that provides pre-configured Docker compositions for deploying Specify applications in containerized environments, available to members upon request. This is the recommended installation method for Specify 7.

## Taxonomy

### Building Trees

- [Taxa Tree Generator](https://github.com/specify/taxa_tree_docker) - A tool for creating taxon tree files for import via the Specify WorkBench based on source data from GBIF, WoRMS, Catalogue of Life, and ITIS. It is especially useful during conversions. Users often request trees along with a list of names, such as families, genera, or species, and we use that list to select the appropriate names and ranks.

   ![Taxa Tree Generator](https://github.com/user-attachments/assets/04c1145f-13a4-40af-8b0c-f42b9abd2e67)

### Importing Synonyms

- [Specify7-Api-Demo](https://github.com/melton-jason/Specify7-Api-Demo/tree/main) by [@melton-jason](https://github.com/melton-jason/): Currently in Specify 7, there is not an easy way using the frontend interface (or the WorkBench component) to **mass-import synonymized** Taxa. This demo aims to create an application that reads a CSV file with taxonomic information to upload new taxa to a Specify 7 instance and update existing taxa with the latest data from the file.

## Testing

- [Specify 7 Test Panel](https://github.com/specify/specify7-test-panel) - A powerful utility to manage and deploy a cluster of Specify 7 instances for testing with automatic deployment, authentication and a test panel for setting configuration. Used internally at Specify.

   ![Test Panel](https://github.com/user-attachments/assets/636539f4-6ab2-4101-bb14-c7fab9ffef89)


## Miscellaneous

- [Sp7APIToolbox](https://github.com/NHMDenmark/Sp7ApiToolbox) by [NHMDenmark](https://github.com/NHMDenmark) - Aimes to gather different code classes, named tools, for interacting with the Specify7 API allowing for bulk actions. For the time being it will run from a command line and can be run directly in a development environment. Pending needs, a fully functional release may be published eventually, perhaps even with a graphical user interface.

