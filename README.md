# Remote Provisioning Schema
## by Microsoft 365 Patterns and Practices (PnP)
This is the Community Source Code location for the PnP remote provisioning schema designed to be used as remote 
creation instructions for remote provisioning engine towards Microsoft 365. 

This is community driven effort for designing one schema which can be used to define elements in the Microsoft 365. 
Initial versions will concentrate on SharePoint, but target is to define also other services using this same structure. 

This effort is closely related on the work being done in the 
[Microsoft 365 Patterns and Practices PnP Framework Library repository](https://github.com/pnp/pnpframework) on actual engine, 
which will provision SharePoint sites and other elements using this schema. 

![Microsoft 365 Patterns and Practices](https://raw.githubusercontent.com/pnp/media/master/pnp-logos-sp/png/1x/SharePoint_PnP_mark_fullcolor.png)

# Version

# Current default implemented version (in the PnP Provisioning Engine) 

[Version 202209](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2022-09.xsd)

## Current approved versions

[Version 202209](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2022-09.xsd)

In order to reference the schema version 202103 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2022/09/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2022/09/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2022-09.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 202103](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2021-03.xsd)

In order to reference the schema version 202103 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2021/03/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2021/03/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2021-03.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 202002](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2020-02.xsd)

In order to reference the schema version 201909 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2020/02/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2020/02/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2020-02.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201909](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2019-09.xsd)

In order to reference the schema version 201909 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2019/09/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2019/09/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2019-09.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

## Deprecated schema versions

[Version 201903](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2019-03.xsd)

In order to reference the schema version 201903 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2019/03/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2019/03/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2019-03.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201807](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-07.xsd)

In order to reference the schema version 201807 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2018/07/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2018/07/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-07.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201805](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-05.xsd)

In order to reference the schema version 201805 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2018/05/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2018/05/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-05.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201801](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-01.xsd)

In order to reference the schema version 201801 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2018/01/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2018/01/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2018-01.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201705](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2017-05.xsd)

In order to reference the schema version 201705 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2017/05/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2017/05/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2017-05.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201605](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2016-05.xsd)

In order to reference the schema version 201605 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2016/05/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2016/05/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2016-05.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

[Version 201512](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-12.xsd)

In order to reference the schema version 201512 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2015/12/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2015/12/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-12.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```


[Version 201508](OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-08.xsd)

In order to reference the schema version 201508 you can use the following syntax:

```xml
<pnp:Provisioning xmlns:pnp="http://schemas.dev.office.com/PnP/2015/08/ProvisioningSchema"
                  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                  xsi:schemaLocation="http://schemas.dev.office.com/PnP/2015/08/ProvisioningSchema https://raw.githubusercontent.com/OfficeDev/PnP-Provisioning-Schema/master/OfficeDevPnP.ProvisioningSchema/ProvisioningSchema-2015-08.xsd">
	<!-- All the schema contents -->
</pnp:Provisioning>
```

## More information
More information and documentation can be found here:

* [Remote Provisioning Schema Documentation - 202209](ProvisioningSchema-2022-09.md)

* [Remote Provisioning Schema Documentation - 202103](ProvisioningSchema-2021-03.md)

* [Remote Provisioning Schema Documentation - 202002](ProvisioningSchema-2020-02.md)

* [Remote Provisioning Schema Documentation - 201909](ProvisioningSchema-2019-09.md)

* [Remote Provisioning Schema Documentation - 201903 - Deprecated](ProvisioningSchema-2019-03.md)

* [Remote Provisioning Schema Documentation - 201807 - Deprecated](ProvisioningSchema-2018-07.md)

* [Remote Provisioning Schema Documentation - 201805 - Deprecated](ProvisioningSchema-2018-05.md)

* [Remote Provisioning Schema Documentation - 201801 - Deprecated](ProvisioningSchema-2018-01.md)

* [Remote Provisioning Schema Documentation - 201705 - Deprecated](ProvisioningSchema-2017-05.md)

* [Remote Provisioning Schema Documentation - 201605 - Deprecated](ProvisioningSchema-2016-05.md)

* [Remote Provisioning Schema Documentation - 201512 - Deprecated](ProvisioningSchema-2015-12.md)

* [Remote Provisioning Schema Documentation - 201508 - Deprecated](ProvisioningSchema-2015-08.md)

* [List of Tokens supported by the PnP Provisioning Engine](https://github.com/OfficeDev/PnP-Sites-Core/blob/master/Core/ProvisioningEngineTokens.md)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


