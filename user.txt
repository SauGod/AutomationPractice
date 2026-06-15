For macOS platforms:
-------------------
	SophosConnect_1.4_MR1(IPsec).pkg: 

		- Sophos Connect 1.4_MR1 supports only IPsec remote access VPN.
                - Fixed issues.

For Windows platforms:
---------------------
	SophosConnect_2.4_0(IPsec_and_SSLVPN).msi: 
	
	- New Features
	 
		•	Azure AD SSO Support (Windows) Single Sign-On (SSO) is now supported for Sophos Connect on Windows. This enables users to authenticate seamlessly using their Azure AD credentials.
			
			Requirements:
			•	SFOS version 21.5 or higher
			
	- Component Updates
		
		•	miniz : 2.1.0 -> 3.0.2
		•	json c++ parser : 3.6.1 -> 3.11.3
		•	openssl :   3.3.2 -> 3.3.3
		•	tinyxml2 : 7.1.0 -> 11.0.0
		
	- Fixes and Improvements
	
		•	Crash Fixes: Resolved stability issues reported from the field.
		•	Security Fixes: Addressed multiple vulnerabilities in third-party components and internal modules.

	Scadmin(legacy).msi:  
		
		- SFOS version 18.0 MR4 and up, will provide functionality to configure the advanced settings for IPsec remote access VPN policy on the web admin console.
		- Tool to configure advanced settings for IPsec remote access VPN policy while running SFOS version 18.0 MR3 and older.
		- To configure the advanced settings, install the tool. For more details, go to https://docs.sophos.com/nsg/sophos-connect/configuration/en-us/scon_cg.html
