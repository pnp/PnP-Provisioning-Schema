# PnP.Provisioning.Schema Changelog

*Please do not commit changes to this file, it is maintained by the repo owner.*

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [vNext]

### Added
-

### Changed
-

## [2018-07]

### Added
- Default Columns Values for Folders (arjenbloemsma)
- Added attributes for AssociatedGroups, AssociatedOwnerGroup, AssociatedMemberGroup, AssociatedVisitorGroup in Security (jensotto)
- Added attributes for RemoveExistingUniqueRoleAssignments and ClearSubscopes in Security (jensotto)
- Added support for property bag properties for RootFolder of lists and libraries (jensotto)
- Added ReuseChildren, IsPinned, IsPinnedRoot attributes to Term element (jensotto)
- Added attribute QuickLaunchEnabled to WebSettings
- Added attribute ContentTypeID to ClientSidePage
- Added element FieldsValues to ClientSidePage

### Changed
- Changed the DisplayName attribute of FieldRef for ListInstance to required
- Removed attributes StorageMaximumLevel, StorageWarningLevel, UserCodeMaximumLevel, and UserCodeWarningLevel from SiteCollection element of Sequence
- Changed the Sequence element to support sequences of "modern" Site Collections and Sub-Sites
- Updated attributes for SiteCollection and Site element in the Sequence element
