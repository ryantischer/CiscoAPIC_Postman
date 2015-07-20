# CiscoAPIC_Postman
Collection of APIC configurations to run within Google Postman.

You must login via the one of the login commands BEFORE running any other commands.  THe login command captures a token
that timesouts and the user will have to reauthenicate.  If your command returns..
	  "code": "403",
          "text": "Token was invalid (Error: Token timeout)"

Use the login command and try again

Requires a Postman environment to be configured with the CASE sensitive data as follows

	URL = IP address of APIC
	TENANTNAME = Name of Tenant to create
	USERNAME = APIC username
	Password = password of APIC
	SYSLOGNAME = name of syslog object to create
	SYSLOGDEST = IP address of syslog server

Included is an example environment that can be imported.  I recomend editing the file with site specific infomation before importing.  

Details, including Postman setup and usage found here...

http://policyetc.com/post/google-postman-and-aci-download-the-collection




