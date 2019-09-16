# PnP.Provisioning.Schema Changelog

*Please do not commit changes to this file, it is maintained by the repo owner.*

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [vNext]

### Added
-

### Changed
-

## [2019-09]

### Added
- Support for Drive (OneDrive for Business and SharePoint Online) provisioning
- Support for User Profile provisioning
- Support for Group Lifecycle Policies provisioning
- Support for Office 365 Groups Settings provisioning
- SiteSettings section
- Support for Attachments in DataRows for list items
- Properties for Folders, to support DataSets
- Vertical sections in Client Side Pages
- Teamify and HideTeamify attributes for sites
- GroupLifecyclePolicyId attribute for Site Collections in sequences
- DiscoverySettings to Teams
- IDs for Tabs and Channels in Teams
- Attribute AllowToAddGuests to pnp:TeamSecurity complex type

### Changed
- WebSettings section, adding more properties
- Updated list of native Client Side Web Parts

## [2019-03]

### Added
- Support for provisioning of Teams in Microsoft Teams
- Support for provisioning of Users in Azure Active Directory
- Support for Theme local to a Site Collection
- Support for Site Header in modern sites
- Support for Site Footer in modern sites
- Support for provisioning Webhooks
- Support for Search Navigation in sites
- Attribute ClearExistingItems for users list
- Attribute TemplateInternalName for list templates
- Attribute UpdateChildren for FieldRef in content types
- Support for Layout of Header for Client Side Pages 
- Support for TextAlignment of Header for Client Side Pages 
- Attributes ShowTopicHeader, ShowPublishDate, TopicHeader, AlternativeText, Authors, AuthorByLine, AuthorByLineId of Header for Client Side Pages 
- Support for Properties in Client Side Pages
- Attribute PromoteAsTemplate in Client Side Pages
- Attribute MenuStyle for Site Header in modern sites
- Attribute BackgroundEmphasis for Site Header in modern sites
- Support for FooterLinks for Site Footer in modern sites
- Attributes Logo, Name, Enabled, RemoveExistingNodes for Site Footer in modern sites
- Attribute NoDefaultOrigins for CDN settings
- Attribute HubSiteLogoUrl for a Hub Site

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
- Added elements to support Themes ad Tenant level
- Added attribute to support Theme at SiteCollection and Site level in Sequences

### Changed
- Changed the DisplayName attribute of FieldRef for ListInstance to required
- Removed attributes StorageMaximumLevel, StorageWarningLevel, UserCodeMaximumLevel, and UserCodeWarningLevel from SiteCollection element of Sequence
- Changed the Sequence element to support sequences of "modern" Site Collections and Sub-Sites
- Updated attributes for SiteCollection and Site element in the Sequence element
