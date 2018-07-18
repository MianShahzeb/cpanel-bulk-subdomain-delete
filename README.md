# Name: cPanel Bulk Subdomains Removal 1.1
	Delete hunderds of Sub Domains with one click from cPanel with simple php script updated 2018 with cPanel API 2
	
# Requirements to configure
1. php file configurations
2. txt file subdomains 

# Upload index.php and file.txt to public_html/[folder]

1. cPanel Username
2. cPanel Password
3. cPanel Skin
4. Root Domain Name
5. Upload file.txt to public_html or any directory (line 26)
			Domains sample
			sub-domain
			subdomain2
			subdomain5
		Each line must contain on 1 sub domain in file.txt
6. Structure of $request
7. Don't forget to sign in into your cpanel and check if you have the same prefix (cpsess16xxxxxx55) (line 47)
8. === Request structure
		https://[host here]:[port here]/cpsess/frontend/cpanel_skin/subdomain/dodeldomain.html?domain=[sub-domain here].[domain here]
9. Sample:
		/$cpess/frontend/$cpanel_skin/subdomain/dodeldomain.html?domain=$subd.$domain
10. Port should be 2083 or 2082 (Normally it will be 2083 by default).

# Credits & Thanks
Thanks to http://www.zubrag.com/scripts/cpanel-delete-subdomains.php but it was not working.
cPanel Hosting https://hosting.biz
IBX Technologies https://ibxtechnologies.com
cPanel https://cpanel.net / http://documentation.cpanel.net/display/CKB/cPanel+Knowledge+Base

