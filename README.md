# Organize Insert Options Rules

This project contains a pipeline processor for the `uiGetMasters` pipeline that allows you to organize your Insert Options Rules however you like in the content tree.

## Usage

1. Install a new instance of [Sitecore 8.2 Update-3](https://dev.sitecore.net/Downloads/Sitecore_Experience_Platform/82/Sitecore_Experience_Platform_82_Update3.aspx).
2. Update the `publishUrl` in the [publish profile](OrganizeInsertOptionsRules/Properties/PublishProfiles/Local.pubxml) to point to your Sitecore installation.
3. Update the `physicalRootPath` in [CustomSerializationFolder.config](OrganizeInsertOptionsRules/App_Config/Include/z.OrganizeInsertOptionsRules.Serialization/CustomSerializationFolder.config) to point to the correct path on your disk.
4. Publish the solution.
5. Enjoy.
