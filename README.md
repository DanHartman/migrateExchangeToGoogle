# Migrating From Microsoft Exchange to Google Apps

[guide](https://www.bettercloud.com/migrating-from-rackspace-to-google-apps)
```
Ok, stream of consciousness here.
what the hell is LDAP
what the hell is Microsoft ActiveDirectory
```

*  Choose Migration Tool(s)
    1.  Which kind of service is used at exchange host?
    
*  Prepare everyone
    1.  Inform everyone about the process
    2.  Brace for impact because fuckall will happen
    3.  Provide support to users

*  Technical Preparations
    1.  Setup Google Account.  Create admin account first?
    2.  Admin Account Acces to Rackspace/host.
    3.  Admin account access to registrar

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
   