**Project Description**
This is a utility allowing admins of Dynamics CRM Online & onPrem (2011-2015) to edit their organization database settings otherwise known as OrgDBOrgSettings

This utility allows you to edit your settings without the use of the command line utility in the KB article documenting "OrgDBOrgSettings."  The utility is written using the CRM SDK as a reference and currently all changes and retrieval of settings are done via the CRM's OData Endpoint.  The utility is provided as a managed webresource that can easily be installed and uninstalled from your CRM environment.  

**Where to I find it after installing?**
The OrgDBSettings utility is installed as a managed CRM solution. As a result I have decided to keep it out of the sitemap and leave it as a Configuration Page in the solution.  To find the editor, go to "Settings", then "Solutions", within the solutions double click on "Organization Settings Editor" this will launch the solution configuration automatically. 
_Note: During beta testing I received feedback asking for the utility to have it's own place in the sitemap however, after discussing with some partners and developers they suggested leaving it out due to possible dependency conflicts._

Browser Supportability: 
- Pre CRM UR12 supported in IE8, 9, 10, and 11
- CRM UR12 (without HTC's) and higher along with this editor is supported in IE8, IE9, IE10, IE11, Chrome, Firefox, and Safari on Mac. 
- NOTE for IE8/9: you must be running in standards mode.  View this documentation for details. [IE8 Settings](IE8-Settings) 
- NOTE: Some IE8/9 configurations block XDR's (cross domain requests) and thus will not get the benefit of update warnings - if you're impacted by this you can use IE10, Chrome, or Firefox - alternatively keep checking back on this site for updates. 
- If you're using IE8, IE9, or IE10 please read this article on [CRM Disable IE Compatibility Mode](CRM-Disable-IE-Compatibility-Mode)

[View Image](http://download-codeplex.sec.s-msft.com/Download?ProjectName=orgdborgsettings&DownloadId=804138)
![](Home_OrgDbOrgSettings2013UR1.png)

The importing of this managed solution will include the following components: 
- JQuery 1.10.1 [http://jquery.com/](http://jquery.com/)
- JSON2 [http://www.json.org/](http://www.json.org/)
- OrgDBOrgSettings.html [How to use the editor](How-to-use-the-editor)
- settings.xml [What is Settings.xml](What-is-Settings.xml)
- AzureMobile [Azure Portal](http://manage.windowsazure.com), MSDN [AzureMobile Services](http://msdn.microsoft.com/en-us/library/windowsazure/jj554228.aspx), and [AzureMobile Preview Signup](http://manage.windowsazure.com/?WT.mc_id=IXT001_prelimtext2012preview_MSDNLibrary)
