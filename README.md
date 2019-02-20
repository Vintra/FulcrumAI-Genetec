# Vintra Module for Genetec

Genetec plugin to interact with Vintra System. 

# Dependencies - for development

- Windows Machine
- [Genetec SDK](https://downloadcenter.genetec.com/products/SecurityCenter/5.7/GA/SDK/Security_Center_v_5_7_GA_b374_105_SDK.exe)
- [Genetec Security Desk 5.7+](https://portal.genetec.com/support/SystemManagement/DownloadSection)
- Install [Rider](https://www.jetbrains.com/rider/download/#section=windows) (or Visual Studio)
- Clone the [repository of plugin](https://github.com/Vintra/genetec-plugin)

# Compile it

Clone this repository.

```
git clone https://github.com/Vintra/genetec-plugin
```

The next step is open the project with Ryder (or Visual Studio), update the code, compile it and build the solution. After that the compiled files, and all necesary files to install in a production will be available in debug (or Release) folder inside bin folder.

# Installation

Download the last version of setup file from [releases](https://github.com/Vintra/genetec-plugin/releases)

Be sure that your Security Desk is closed.

Run with administrator permisions the setup file. You can do it clicking (right button) on Vintra.Plugin.exe file and select "Execute as administrator". This will install the plugin in your system.

# Getting Started


Open Security Desk application.

Locate the new feature in your main panel of Genetec Security Desk. The Vintra Module has a Vintra icon ![alt text](https://github.com/Vintra/genetec-plugin/blob/master/VintraModule/Resources/logo16.png "Vintra Logo") and it's located inside "Vintra System Module" category.

You can find it using the Genetec search input typing Vintra.

Now you are able to access to the new feature to interact with Vintra System, but before it you need to configure the plugin.

## Configuration 

You must configure the plugin in order to it connects to Vintra System. After click on Vintra task, if it isn't properly configured, an configuration page will be open automaticaly.

In this page you need to introducre the IP of the server where is located the API and a valid access token to authoritze the petitions.

## Next Steps

If you have the plugin configured well, you are ready to use all features. Explore in all sections and see what Vintra can do for you:

<dl>
    <dd>Search: Analyze area that provide a interface to see results of your querys in a cameras. You can find objects (What) os subjects (Who) in cameras (Where) in a defined time range (When).</dd>
    <dd>Camera: Configure the indexation of cameras. In order to apply search in cameras, it needs to be processed by Vintra System, in this section you can enable the indexation for each camera.</dd>
    <dd>Subjects: Manage your dataset of subjects to can search in the analyze area.</dd>
    <dd>Configuration: Change the plugin configuration parameters.</dd>
</dl>

