# AzureBlobUtility
Contains methods to access, list and write the contents from/to Blob files under Azure Storage Account.

1. Read Blob files from Storage Account
2. Write Blob files into Storage Account

This solution has 2 projects

#AzureBlobUtility - .Net Class Library which containe utility methods for Azure Blob.

#BlobUtilityTest - ASP.NET Core Web API Contains web api project which makes use of AzureBlobUtility library. Dependency injection and Azure Storage Account setup for the AzureBlobUtility is performed under Program.cs file.
