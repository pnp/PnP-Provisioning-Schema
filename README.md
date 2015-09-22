# Remote Provisioning Schema
## by Office 365 Patterns and Practices
This is the Community Source Code location for the PnP remote provisioning schema designed to be used as remote 
creation instructions for remote provisioning engine towards Office 365. 

This is community driven effort for designing one schema which can be used to define elements in the Office 365. 
Initial versions will concentrate on SharePoint, but target is to define also other services using this same structure. 

This effort is closely related on the work being done in the 
[Office 365 Developer Patterns and Practices repository](https://github.com/OfficeDev/PnP) on actual engine, 
which will provision SharePoint sites and other elements using this schema. 

# Version

# Current implemented version (in the PnP Provisioning Engine) 

[Version 201505](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-05.xsd)

## Current approved versions

[Version 201508](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-08.xsd)

In order to reference the schema version 201508 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2015/08/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2015/08/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-08.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```


[Version 201505](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-05.xsd)

In order to reference the schema version 201505 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2015/05/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2015/05/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-05.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

## More information
More information and documentation can be found here:

* [Remote Provisioning Schema Documentation - 201508](ProvisioningSchema-2015-08.md)

* [Remote Provisioning Schema Documentation - 201505](ProvisioningSchema-2015-05.md)


