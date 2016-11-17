# Migrating From Microsoft Exchange to Google Apps
[google signup]: https://www.google.com/a/signup/?hl=en&source=gafb-homepage-canvas-&ga_region=noram&ga_country=us&ga_lang=en#0
[guide]: https://www.bettercloud.com/migrating-from-rackspace-to-google-apps
[google apps sync]: https://tools.google.com/dlpage/gappssync/
[setup gssmo]: https://support.google.com/a/answer/148484#Googleappsreqs
[gssmo how to]:https://support.google.com/a/users/answer/153871

*  Choose Migration Tool(s)
    2.  [example how to guide][guide]
    3.  [Sync Tool How-To][gssmo how to]
    
*  Prepare everyone
    1.  Inform everyone about the process
    2.  Brace for impact because fuckall will happen
    3.  Provide support to desktop users
    4.  Provide support to mobile users

*  Technical Preparations
    1.  [google signup][google signup] Create admin account first
    3.  [Enable GSSMO][setup gssmo] in the admin pane
    2.  Create List of new accounts
    2.  Admin account access to Rackspace/host.
    3.  Admin account access to registrar
    4.  Get Users to install the [GASMO][google apps sync] tool

*  Test Migrate single account

*  Reconfigure DNS
   1.  This is where service will be interrupted
   2.  Choose best time to do this.  Friday evening?  TTL may be up to 48 hours
   
   `Priority    Mail Server`

   `1   ASPMX.L.GOOGLE.COM.`

   `5   ALT1.ASPMX.L.GOOGLE.COM.`

   `5   ALT2.ASPMX.L.GOOGLE.COM.`

   `10  ALT3.ASPMX.L.GOOGLE.COM.`

   `10  ALT4.ASPMX.L.GOOGLE.COM.`
