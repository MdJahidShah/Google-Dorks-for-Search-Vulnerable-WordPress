# Google Dorks for Searching Vulnerable WordPress Sites

This repository provides a comprehensive list of **Google Dorks** to help identify vulnerable WordPress websites. These dorks can assist security researchers in finding specific vulnerabilities and taking proactive steps to fix them. **Note**: These are intended solely for ethical and educational purposes to enhance cybersecurity awareness.

## List of Google Dorks

### General WordPress Endpoints:
- `inurl:wp-login.php`
- `inurl:wp-admin`
- `inurl:xmlrpc.php`
- `inurl:readme.html`
- `intitle:"index of" "wp-config.php"`

### Registration and Login:
- `inurl:wp-login.php?action=register`
- `inurl:wp-login.php intitle:"index of" "wp-config.php"`

### Plugins:
- `inurl:wp-content/plugins`
- `inurl:wp-content/plugins/wp-file-manager`
- `inurl:wp-content/plugins/wordpress-backup`
- `inurl:wp-content/plugins/wp-db-backup`
- `inurl:wp-content/plugins/wp-maintenance-mode`
- `inurl:wp-content/plugins/wp-postratings`
- `inurl:wp-content/plugins/wp-touch`
- `inurl:wp-content/plugins/broken-link-checker`
- `inurl:wp-content/plugins/wp-smush`
- `inurl:wp-content/plugins/wp-super-cache`
- `inurl:wp-content/plugins/jetpack`
- `inurl:wp-content/plugins/wordfence`
- `inurl:wp-content/plugins/akismet`
- `inurl:wp-content/plugins/contact-form-7`
- `inurl:wp-content/plugins/yet-another-related-posts-plugin`
- `inurl:wp-content/plugins/nextgen-gallery`
- `inurl:wp-content/plugins/all-in-one-seo-pack`
- `inurl:wp-content/plugins/google-analytics-for-wordpress`
- `inurl:wp-content/plugins/google-sitemap-generator`
- `inurl:wp-content/plugins/google-xml-sitemaps`
- `inurl:wp-content/plugins/wp-seo`
- `inurl:wp-content/plugins/wp-google-maps`
- `inurl:wp-content/plugins/wp-e-commerce`
- `inurl:wp-content/plugins/wp-easycart`
- `inurl:wp-content/plugins/woocommerce`
- `inurl:wp-content/plugins/bbpress`
- `inurl:wp-content/plugins/buddypress`
- `inurl:wp-content/plugins/easy-digital-downloads`
- `inurl:wp-content/plugins/event-espresso`
- `inurl:wp-content/plugins/gravity-forms`
- `inurl:wp-content/plugins/w3-total-cache`
- `inurl:wp-content/plugins/wp-rocket`
- `inurl:wp-content/plugins/wp-optimize`
- `inurl:wp-content/plugins/autoptimize`
- `inurl:wp-content/plugins/advanced-custom-fields`
- `inurl:wp-content/plugins/custom-post-type-ui`
- `inurl:wp-content/plugins/pods`
- `inurl:wp-content/plugins/toolset-types`
- `inurl:wp-content/plugins/wpml-string-translation`
- `inurl:wp-content/plugins/wpml-translation-management`

### Themes:
- `inurl:wp-content/themes`

### Uploads, Cache, and Backup:
- `inurl:wp-content/uploads`
- `inurl:wp-content/cache`
- `inurl:wp-content/upgrade`
- `inurl:wp-content/backup`


## WordPress Vulnerability Scanning Tools
Here's the formatted list you requested:  

---

1. **WPScan**: WPScan is a popular WordPress security scanner written for security professionals and blog maintainers to test the security of their WordPress websites. For real-time vulnerability data, it uses the WordPress Vulnerability Database API.  
   - **URL**: [WPScan](https://github.com/wpscanteam/wpscan)  

2. **HackerTarget.com**: HackerTarget.com offers an online WordPress security scanner that tests for vulnerabilities in a WordPress installation. It includes checks for application security, WordPress plugins, hosting environment, and web server.  
   - **URL**: [HackerTarget.com](https://hackertarget.com/wordpress-security-scan/)  

3. **Pentest-Tools.com**: This tool helps discover security issues and vulnerabilities in WordPress websites using the WPScan scanner. It performs multiple tests to identify security weaknesses remotely, simulating an external attacker.  
   - **URL**: [Pentest-Tools.com](https://pentest-tools.com/cms-vulnerability-scanning/wordpress-scanner-online-wpscan)  

4. **Sucuri**: Sucuri offers a comprehensive security solution for WordPress, including a vulnerability scanner that checks for malware, blacklisting status, and other security issues.  
   - **URL**: [Sucuri](https://www.wpwebsitehelp.com/wordpress-security-vulnerabilities-scanner-tool/)  

5. **Wordfence**: Wordfence is a WordPress security plugin that includes a vulnerability scanner, firewall, and malware removal tools. It scans for known vulnerabilities in WordPress core, themes, and plugins.  
   - **URL**: [Wordfence](https://www.wpwebsitehelp.com/wordpress-security-vulnerabilities-scanner-tool/)  

6. **WPRecon**: WPRecon is an online tool that scans WordPress for vulnerabilities and provides detailed information about each one. It helps identify and fix security issues in WordPress installations.  
   - **URL**: [WPRecon](https://www.wpwebsitehelp.com/wordpress-security-vulnerabilities-scanner-tool/)  

7. **GeekFlare Vulnerability Scanner**: GeekFlare offers a free vulnerability scanner for WordPress that checks for common security issues and provides recommendations for improving security.  
   - **URL**: [GeekFlare](https://www.wpwebsitehelp.com/wordpress-security-vulnerabilities-scanner-tool/)  

8. **VirusTotal**: VirusTotal is a free online service that analyzes files and URLs for viruses, worms, trojans, and other kinds of malicious content. It can be used to scan WordPress files for malware.  
   - **URL**: [VirusTotal](https://www.wpwebsitehelp.com/wordpress-security-vulnerabilities-scanner-tool/)  

9. **Netsparker**: Netsparker is a web application security scanner that can identify vulnerabilities in WordPress websites. It offers both online and offline scanning options.  
   - **URL**: [Netsparker](https://www.netsparker.com/)  

10. **Acunetix**: Acunetix is a web vulnerability scanner that can detect vulnerabilities in WordPress websites. With this software, you can scan and report comprehensively.  
   - **URL**: [Acunetix](https://www.acunetix.com/)  

11. **Detectify**: Detectify is a web security scanner that can identify vulnerabilities in WordPress websites. It offers automated scanning and detailed reports.  
   - **URL**: [Detectify](https://detectify.com/)  

12. **SiteLock**: SiteLock offers a website security solution that includes a vulnerability scanner for WordPress websites. It can detect and fix security issues automatically.  
   - **URL**: [SiteLock](https://www.sitelock.com/)  

13. **Quttera**: Quttera offers a malware and vulnerability scanner for WordPress websites. It can detect malicious code and security vulnerabilities.  
   - **URL**: [Quttera](https://quttera.com/)  

14. **UpGuard**: UpGuard offers a website security scanner that can identify vulnerabilities in WordPress websites. It provides detailed reports and recommendations for improving security.  
   - **URL**: [UpGuard](https://www.upguard.com/)  

15. **Astra Security**: Astra Security offers a comprehensive security solution for WordPress websites, including a vulnerability scanner that checks for malware, blacklisting status, and other security issues.  
   - **URL**: [Astra Security](https://www.getastra.com/)  

16. **MalCare**: MalCare is a WordPress security plugin that includes a vulnerability scanner, firewall, and malware removal tools. It scans for known vulnerabilities in WordPress core, themes, and plugins.  
   - **URL**: [MalCare](https://www.malcare.com/)  

17. **WordPress Security Scan**: WordPress Security Scan is an online tool that scans WordPress websites for vulnerabilities and provides detailed reports on security issues.  
   - **URL**: [WordPress Security Scan](https://wordpress.org/plugins/wp-security-scan/)  

18. **WP Neuron**: WP Neuron offers a vulnerability scanner for WordPress websites that can detect security issues and provide recommendations for improving security.  
   - **URL**: [WP Neuron](https://wpneuron.com/)  

19. **WP White Security**: WP White Security offers a range of security tools for WordPress websites, including a vulnerability scanner that checks for known security issues.  
   - **URL**: [WP White Security](https://www.wpwhitesecurity.com/)  

20. **WP Hacked Help**: WP Hacked Help offers a vulnerability scanner for WordPress websites that can detect and fix security issues. It also provides malware removal and website cleanup services.  
   - **URL**: [WP Hacked Help](https://www.wphackedhelp.com/)  

---
### Disclaimer:
This information is provided for ethical purposes only. Misuse of these Google dorks for malicious intent is against ethical guidelines and may violate laws. Always obtain proper authorization before testing or auditing any website. To know more, read my blog about [WordPress Security](https://jahidshah.com/category/website-security/).  
