# github-page-hijackers
This repo containing list of github user that might hijack your domain through github pages.


Recently, I encountered a concerning incident where my domain was hijacked through an exploit involving default DNS records set up by my domain provider. This repo  aims to raise awareness about this issue and provide preventive measures to secure your online presence.

## The Vulnerability
Most domain providers automatically generate default DNS records for various services, such as FTP, WWW, and email. In my case, the FTP record was set up as a CNAME (Canonical Name) alias, pointing to the primary domain (e.g., foobar.com).

While I had correctly configured GitHub Pages for foobar.com, I overlooked the FTP record. An unauthorized party exploited this oversight by creating a GitHub Pages repository for ftp.foobar.com. They then gained control over this subdomain. They even could do verifying domain ownership through Google Search Console, by using HTML verifications.

## Prevention
To prevent such subdomain hijacking incidents when using GitHub Pages, it is crucial to consistently verify your domain ownership through the official GitHub Pages settings: https://github.com/settings/pages

## Call to Action
If you have encountered a similar issue or have identified subdomains that may have been hijacked, please contribute to this repository by listing the affected accounts. Together, we can raise awareness and help secure the online presence of GitHub Pages users.

Github Account list:
* https://github.com/Orelnazua66/ftp.sysctl.id
