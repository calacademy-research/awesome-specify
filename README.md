<p align="center">
  <br>
  <img width="200" src="https://github.com/user-attachments/assets/46d6c42e-aea5-47d4-90d9-27194f759ea3" alt="logo of awesome-specify repository">
  <br>
  <br>
</p>

# Awesome Specify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A community-driven list of Specify integrations, software, and resources developed by the community.

Please see the official Specify code repositories at [https://github.com/specify](https://github.com/specify).

## Repositories

#### Taxonomy

[Taxa Tree Generator](https://github.com/specify/taxa_tree_docker) - A tool for creating taxon tree files 
for import via the Specify WorkBench based on source data from GBIF, WoRMS, Catalogue of Life, and ITIS. 
It is especially useful during conversions. Users often request trees along with a list of names, such as 
families, genera, or species, and we use that list to select the appropriate names and ranks.

[Specify7-Api-Demo](https://github.com/melton-jason/Specify7-Api-Demo/tree/main) by 
[@melton-jason](https://github.com/melton-jason/): Currently in Specify 7, there is not an easy way using 
the frontend interface (or the WorkBench component) to **mass-import synonymized** Taxa. This demo aims 
to create an application that reads a CSV file with taxonomic information to upload new taxa to a 
Specify 7 instance and update existing taxa with the latest data from the file.

#### Miscellaneous / mixed

[Sp7APIToolbox](https://github.com/NHMDenmark/Sp7ApiToolbox) by [NHMDenmark](https://github.com/NHMDenmark) - Aimes to gather 
different code classes, named tools, for interacting with the Specify7 API allowing for bulk actions. For the time being it 
will run from a command line and can be run directly in a development environment. Pending needs, a fully functional release 
may be published eventually, perhaps even with a graphical user interface.

[SpecifyUtilities](https://github.com/NSCF/SpecifyUtilities): 
A mishmash of scripts developed by the [Natural Science Collections Facility](https://nscf.org.za/) for doing various things in 
Specify, including batch copying queries from one user to several others, extracting data in Darwin Core format, updating catalog 
numbers, updating parasite hosts, updating synonyms, etc. See importBRAHMS8Checklist for importing a flat taxon file and constructing
full names for plants. Scripts DO NOT use the API, so beware!

[specify-sort-views](https://github.com/NSCF/specify-sort-views):
Sometimes the XML files that define the Specify forms are a bit untidy, so this formats and sorts the views/viewdefs 
alphabetically to make them easier to work with. Nice to do this with a new Specify instance before starting on form customization.

[specify-sql](https://github.com/NSCF/SpecifySQL): a set of SQL queries I used to quickly get information directly 
from the database while troubleshooting, migrating, etc.

[specify-api-js-client](https://github.com/NSCF/Specify-API-JS-client): An OLD repo for getting started with the 
Specify API, mainly getting the access token, in Javascript. May well no longer work...

[Specify 7 Test Panel](https://github.com/specify/specify7-test-panel) - A powerful utility to manage and deploy a cluster of Specify 7 instances for testing with automatic deployment, authentication and a test panel for setting configuration. Used internally at Specify.

#### Data migration / workbench

[nca-data-migrator](https://github.com/NSCF/nca-specify-migrator):
A script written to migrate a relatively large collection (> 80 000 collection object records) to Specify, 
because the workbench was just too slow. Intended for initial migration only, does not use the API. On a 
local instance migrates all records in ~4 minutes. Can be tweaked to work with other datasets by updating 
mappings.py, although you'll need to add additional table classes under `db` and update `importdata.py` 
if you're importing data into additional tables. Some scripts are a bit messy and may not work, e.g. 
updatesynonyms, which was intended to use World Spider Catalog, but was abandoned in dispair when it was 
discovered that WSC taxon identifiers are moved when names are synonymized. Please CLONE and not FORK 
this repo for migrations on other collections.



