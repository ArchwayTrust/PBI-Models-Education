# PBI Models - Education

## Getting Started
This repository  contains the main Power BI Education model for Archway Learning Trust.

Model is serialised into [Microsoft TMDL format](https://powerbi.microsoft.com/en-us/blog/announcing-public-preview-of-the-tabular-model-definition-language-tmdl/). This is human readable text but can also be opened by newer versions of Tabular Editor 2 if the preview feature is enabled:
[Tabular Editor 2.x Releases](https://github.com/TabularEditor/TabularEditor/releases).

Project adopts Power BI release-branching model layed out in https://pbi.tools/devops/release-branching-model/

## Contributing
An issue should be created with a linked branch names Issue/Issue#-ShortName.
Once complete, use a pull request to merge into the current release candidate branch should be created.

## Deployment
Once TMDL is out of preview and can serialise role membership the intention is to enable continuous deployment into test and production workspaces.
