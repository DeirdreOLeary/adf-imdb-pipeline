# adf-imdb-etl

Purpose: This repo is part of the project to ELT IMDb data from flat files in Azure Blob storage to Azure SQL Database using Azure Data Factory. It contains the ADF project.

The Database schema repository is at https://github.com/DeirdreOLeary/adf-imdb-databases

**Note:** The principalId & tenantId in factory/adf-imdb-to-sqldb-01.json have been identified as potentially sensitive data relating to the owner's Azure tenant & have been removed in the current commit & history. This may result in breaking changes in Azure Data Factory.
