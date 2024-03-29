# Kali Vs WordPress
# Pentesting write-up/report:<br/>
First exploit found: XSS (Cross Site Scripting)<br/>
Summary for exploit 1:         
   - The types / classes of vulnerabilities involved and any related CVE identifiers
      - The vulnerability type is XSS.
      - The CVE Identifier is: CVE-2020-11030
   - Identify affected versions and patches
      - The affected versions and patches are for versions 4.2.2 or older versions. Newer versions are fixed.
   - Links to the source code, where possible
      - https://core.trac.wordpress.org/browser/trunk/src/wp-includes/theme.php
   - Steps to recreate:
      - Enter given command on a newly created page, and hover over and you will see an assert. Follow gif if needed.

![ScreenCap1](https://user-images.githubusercontent.com/96878742/198816347-a3e6bf7f-f7bc-42c9-a4bf-eaab469bb6ca.gif)

Second exploit found: XSS (Cross Site Scripting)<br/>
Summary for exploit 2:         
   - A small writeup indicating the steps you used to recreate
   - The types / classes of vulnerabilities involved and any related CVE identifiers
      - The vulnerability type is XSS.
      - The CVE Identifier is: CVE-2019-16223 
   - Identify affected versions and patches
      - The affected versions and patches are for versions 4.2 or older versions. Newer versions are fixed. 
   - Links to the source code, where possible
      - https://core.trac.wordpress.org/browser/trunk/src/wp-includes/theme.php 
   - Steps to recreate:
      - Enter given command on a newly created post, and hover over and you will see an assert. Follow gif if needed.

![ScreenCap#2](https://user-images.githubusercontent.com/96878742/198817077-7f3cb471-0bd7-44c5-9146-6ec6f8fc7c14.gif)

Third exploit found: XSS (Cross Site Scripting)<br/>
Summary for exploit 3:
   - The types / classes of vulnerabilities involved and any related CVE identifiers
      - The vulnerability type is XSS.
      - The CVE Identifier is: CVE-2019-16223 
   - Identify affected versions and patches
      - The affected versions and patches are for versions 4.2 or older versions. Newer versions are fixed.  
   - Links to the source code, where possible
      - https://core.trac.wordpress.org/browser/trunk/src/wp-includes/class-wp-embed.php 
   - Steps to recreate:
      - Enter given command on a newly created post, and hover over and you will see an assert. Follow gif if needed.

![ScreenCap3](https://user-images.githubusercontent.com/96878742/198817432-4aee6338-21f7-498c-93eb-262a26bd6746.gif)

Fourth exploit found: User Enumeration <br/>
Summary for exploit 4:
   - The types / classes of vulnerabilities involved and any related CVE identifiers
      - The vulnerability type is User Enumeration.
      - The CVE Identifier is: N/A. Most relevant: CVE-2020-35539
   - Identify affected versions and patches
      - The affected versions and patches are for versions 4.2 or older versions. Newer versions are fixed.
   - Links to the source code, where possible
      - https://core.trac.wordpress.org/browser/tags/4.2/src/wp-login.php
   - Steps to recreate:
      - Go to login screen, enter a valid username and incorrect password and it will say the username is valid. Follow gif if needed.

![ScreenCap4](https://user-images.githubusercontent.com/96878742/198817804-3e831e06-e3b6-4691-8cc5-bbe8ad8d55dd.gif)
