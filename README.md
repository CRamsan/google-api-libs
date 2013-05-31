google-api-libs
===============

Set of libraries required to test and develop Apps on top of the Google App Engine and using Google API

What we will need
=================

For Development
---------------

 * Eclipse(Most supported IDE)
 * Google Plugin for Eclipse
   * Google Web Toolkit SDK
   * App Engine SDK
 * Ant

Setup
=====

I assume you have eclipse(latest) installed with JDK7+ and ant(apache-ant)

The best approach found so far was to install the google plugin for eclipse. This plugin will automatically download and configure the GWT and AppEngine SDK. 

The following instructions have been copied from the AppEngine Docs

 * Select the Help menu > Install New Software....
 * In the Work with text box, enter: https://dl.google.com/eclipse/plugin/4.2
 * Click the Add... button. In the dialog that shows, click OK (keep the name blank, it will be retrieved from the update site.)
 * Click the plus icon next to "Google Plugin for Eclipse" and "SDKs". Check the boxes next to "Google Plugin for Eclipse 4.2" and "Google App Engine Java SDK". 
 * You can also select the "Google Web Toolkit SDK" if you'd like to use Google Web Toolkit with your apps. Make sure you check the checkbox labeled "Contact all update sites during install to find required software." Click the Next button. Follow the prompts to accept the terms of service and install the plugin.
 * When the installation is complete, Eclipse prompts you to restart. Click Yes. Eclipse restarts. The plugin is installed.

Reference: https://developers.google.com/appengine/docs/java/tools/eclipse

Now your AppEngine should be installed in your home directory, the path usually is: 
~/.eclipse/org.eclipse.platform_"ECLIPSE_VERSION"/plugins/com.google.appengine.eclipse.sdkbundle_"SDK_VERSION"
And the path for the GWT plugin would be: 
~/.eclipse/org.eclipse.platform_"ECLIPSE_VERSION"/plugins/com.google.gwt.eclipse.sdkbundle_"SDK_VERSION"
