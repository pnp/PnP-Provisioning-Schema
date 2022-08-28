# PnP.Provisioning.Schema Changelog

*Please do not commit changes to this file, it is maintained by the repo owner.*

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [vNext]

### Added
- 

### Changed
-

## [2022-09]

### Added
- Added support for SPFx form customizers in ContentType elements [PaoloPia]
- Added support for collapsible sections in modern pages [LauraKokkarinen]
- Added support for ShowPeoplePickerSuggestionsForGuestUsers in Site Settings [patrikhellgren]
- Added support for ShowBackgroundGradient in modern pages [mhazebroucq]
- Added attributes EnableAudienceTargeting and EnableClassicAudienceTargeting to ListInstance [rlv-dan]
- Added attributes AllowNewMessageFromBots, AllowNewMessageFromConnectors, ReplyRestriction, UserNewMessageRestriction to TeamChannel [czullu]
- Added support for Extended layout in modern Site Header [prawnz,benwharg]

### Changed
- Changed regex for ContentType ID in order to support dynamic arguments [eduardpaul]

## [2021-03]

### Added
- Added DefaultLCID to Localizations
- Added SiteLogoThumbnail to SiteLogoThumbnail WebSettings
- Added EnableAudienceTargeting to Navigation
- Added DefaultColumnValues to ListInstance
- Added UpdateChildren to ContentType
- Added Name and Remove to AllowedContentTypes in DocumentSet
- Added Name and Remove to SharedField in DocumentSet
- Added UpdateChildren to DocumentSetTemplate
- Added ClientSideHostProperties to CustomAction
- Added new Layout types (Extended, Minimal) for site Header
- Added ShowSiteTitle to site Header
- Added ShowSiteNavigation to site Header
- Added Layout to site Footer
- Added DisplayName to site Footer
- Added new native client side web parts (Kindle, MyFeed, OrgChart, SavedForLater, Twitter, WorldClock, SpacesDocLib, SpacesFileViewer SpacesImageViewer, SpacesModelViewer, SpacesImageThreeSixty, SpacesVideoThreeSixty, SpacesText2D, SpacesVideoPlayer, SpacesPeople)
- Added InstallOrUpdate option to Action for Apps
- Added HiddenGroupMembershipEnabled for Teams

## [2020-02]
 
### Added
- Tenant-level settings for sharing
- SearchBoxInNavBar attribute for SiteSettings and WebSettings
- SearchCenterUrl attribute for SiteSettings and WebSettings
- SiteDesing attribute for modern Team site provisioning
- Groupify attribute for STS#03 no-group Team site provisioning
- AllowCreatePrivateChannels in MembersSettings for Team provisioning

### Changed
- 

## [2019-09]

### Added
- Support for Drive (OneDrive for Business and SharePoint Online) provisioning
- Support for User Profile provisioning
- Support for Group Lifecycle Policies provisioning
- Support for Office 365 Groups Settings provisioning
- Alternate UI Cultures for WebSettings and modern multi-linguage experience
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
