#Using BrandCAPTCHA with Joomla - RSForm!Pro

##Installation
The RSForm!Pro - BrandCaptcha Plugin is a Joomla! plugin that once installed and enabled will add anti-spam functionality to your RSForm!Pro installation. In this tutorial, you will learn how to install the plugin, then we will learn how to use the BrandCaptcha component.

##Technical requirements
In order to make the plugin work, you need:
Joomla! 2.5 or 3.0
RSForm! Pro 1.4.0 r47.1
fsockopen PHP function enabled in your server.

##Getting the RSForm!Pro - BrandCaptcha plugin
Simply go https://github.com/PontaMedia/brandcaptcha-plugin-Joomla-RSForm and download the files.

##Installing the plugin
Once you have downloaded the RSForm!Pro Joomla! BrandCaptcha plugin, you can install it using the default Joomla! installer.
The plugin should auto-publish itself, but if that doesn't happen, you can go to Extensions / Plugin Manager and enable it. The plugin is located in the System group and you can identify it by the name of "System - RSForm!Pro BrandCaptcha"

Since this is an unofficial plugin you will need to replace some files in the RSForm! Pro installation in order to make this plugin works. Please remember to make a backup previously.
copy forms.php to  /JOOMLA_PATH/administrator/components/com_rsform/models/forms.php
copy script.rsform.php to /JOOMLA_PATH/administrator/components/com_rsform/script.rsform.php
 

##Configuring the BrandCaptcha Plugin
After installing and enabling the plugin, go to Administrator » RSForm!Pro » Configuration. You will notice that a new tab named BrandCaptcha appeared. That's where you must set up the plugin as follows:
Public Key: - The public key that you have to get from Pontamedia
Private Key: - The private key that you have to get from Pontamedia

##Using the BrandCaptcha form components
Once you have enabled the plugin, go to RSForm!Pro » Manage Forms and edit the form where you want to use the RSForm!Pro - BrandCaptcha plugin. You will notice on the left side of the screen, just under the common form components, the new BrandCaptcha plugin form components.
To add BrandCaptcha  to the form, just click on the "BrandCaptcha" form component. You will have to fill the properties of the component.