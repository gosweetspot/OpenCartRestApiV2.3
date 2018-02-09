# OpenCartRestApiV2.3
GSS Opencart Rest API gateway for OpencartV2.3

# README / INSTALLATION  #

This extension is provided on a as-is basis.

Installation is at your own risk.

The package may be updated from time to time, and these upgrades may break this particular version. You will be required to update.

###ENSURE YOU BACKUP YOUR SITE BEFORE INSTALLING THIS ###

### IT IS RECOMMENDED THAT YOUR GET YOUR WEBSITE ADMIN TO REVIEW THE FILES TO ENSURE IT DOES NOT CONFLICT WITH ANY EXISTING EXTENSIONS ###

Download latest release from https://github.com/gosweetspot/OpenCartRestApiV2.3/releases

You will notice that the folders are in the same structure as your Opencart installation.

1. Navigate to your opencart root folder using an FTP program
2. Upload the "catalog" & "admin" folder to your opencart installation folder
3. Go to your admin area in Extensions->Product Feeds and enable your GSS API extension
   You have to fill the security key field. We recommend you use a strong random password of at least 16 characters (eg. JR.ALd?*QM*b&r2y)
   This key is then required on GoSweetSpot configuration.

If you encounter an error while enabling the extension, you may need to apply the following permission changes:
```
chmod 0777 admin/controller/extension/feed/gss_api.php
chmod 0777 admin/view/template/extension/feed/gss_api.tpl
chmod 0777 catalog/controller/extension/feed/gss_api.php
chmod 0777 catalog/model/account/gss_order.php

```
