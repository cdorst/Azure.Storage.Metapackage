# Azure.Storage.Metapackage

[![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/azure-storage-metapackage.svg?label=AppVeyor&style=for-the-badge)](https://ci.appveyor.com/project/cdorst/azure-storage-metapackage)
[![NuGet package status](https://img.shields.io/nuget/v/CDorst.Azure.Storage.Metapackage.svg?label=NuGet&style=for-the-badge)](https://www.nuget.org/packages/CDorst.Azure.Storage.Metapackage)

## Description

Metapackage for Microsoft Azure Storage dependencies

## Environment Variables

This project depends on this environment variable:

Name | Description
---- | -----------
`LOCAL_NUGET_SOURCE_PATH` | *Required* to build the project, but not required during code execution. This is set to `c:\projects\nuget\cache` on the build server. On your development machine, set this to an empty, existing path. `dotnet restore` will inspect this folder prior to checking NuGet.

## Dependencies

Name | Status
---- | ------
WindowsAzure.Storage | [![NuGet package status](https://img.shields.io/nuget/v/WindowsAzure.Storage.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/WindowsAzure.Storage)

## Dependents

The projects below use this repository as a direct dependency.

Name | Status
---- | ------
[Azure.Storage.Connection.GetCloudStorageAccount](https://github.com/CDorst./Azure.Storage.Connection.GetCloudStorageAccount) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst./azure-storage-connection-getcloudstorageaccount.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst./azure-storage-connection-getcloudstorageaccount) [![NuGet package status](https://img.shields.io/nuget/v/CDorst..Azure.Storage.Connection.GetCloudStorageAccount.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst..Azure.Storage.Connection.GetCloudStorageAccount)
[DevOps.Build.AppVeyor.AzureStorageTableLedger](https://github.com/CDorst./DevOps.Build.AppVeyor.AzureStorageTableLedger) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst./devops-build-appveyor-azurestoragetableledger.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst./devops-build-appveyor-azurestoragetableledger) [![NuGet package status](https://img.shields.io/nuget/v/CDorst..DevOps.Build.AppVeyor.AzureStorageTableLedger.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst..DevOps.Build.AppVeyor.AzureStorageTableLedger)
[DevOps.Build.AppVeyor.AzureStorageTableVersionLedger](https://github.com/CDorst./DevOps.Build.AppVeyor.AzureStorageTableVersionLedger) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst./devops-build-appveyor-azurestoragetableversionledg.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst./devops-build-appveyor-azurestoragetableversionledg) [![NuGet package status](https://img.shields.io/nuget/v/CDorst..DevOps.Build.AppVeyor.AzureStorageTableVersionLedger.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst..DevOps.Build.AppVeyor.AzureStorageTableVersionLedger)
[DevOps.Code.Entities.EntityTypeLedger](https://github.com/CDorst./DevOps.Code.Entities.EntityTypeLedger) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst./devops-code-entities-entitytypeledger.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst./devops-code-entities-entitytypeledger) [![NuGet package status](https://img.shields.io/nuget/v/CDorst..DevOps.Code.Entities.EntityTypeLedger.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst..DevOps.Code.Entities.EntityTypeLedger)

## NuGet


This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.Azure.Storage.Metapackage](https://www.nuget.org/packages/CDorst.Azure.Storage.Metapackage)

## Version

1.0.0

## Metaproject

Azure.Storage.Metapackage is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

