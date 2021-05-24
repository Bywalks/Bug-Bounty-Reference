# Bug Bounty Reference

A list of bug bounty write-up that is categorized by the bug nature, this is inspired by https://github.com/ngalongc/bug-bounty-reference.

# Introduction

I have been reading for Bug Bounty write-ups for a few months, I found it extremely useful to read relevant write-up when I found a certain type of vulnerability that I have no idea how to exploit. This project is used to Record the articles I have read,When I need to query an article, I can find it in time.At the same time, you can find some interesting articles here

- [XSSI](#xssi)
- [Cross-Site Scripting (XSS)](#cross-site-scripting-xss)
- [Brute Force](#brute-force)
- [SQL Injection (SQLi)](#sql-injection)
- [External XML Entity Attack (XXE)](#xxe)
- [Remote Code Execution (RCE)](#remote-code-execution)
  - [Deserialization](#deserialization)
  - [Image Tragick](#image-tragick)
- [Cross-Site Request Forgery (CSRF)](#csrf)
- [Insecure Direct Object Reference (IDOR)](#direct-object-reference-idor)
- [Stealing Access Token](#stealing-access-token)
  - [Google Oauth Login Bypass](#google-oauth-bypass)
- [Server Side Request Forgery (SSRF)](#server-side-request-forgery-ssrf)
- [Unrestricted File Upload](#unrestricted-file-upload)
- [Race Condition](#race-condition)
- [Business Logic Flaw](#business-logic-flaw)
- [Authentication Bypass](#authentication-bypass)
- [HTTP Header Injection](#http-header-injection)
- [Email Related](#email-related)
- [Money Stealing](#money-stealing)
- [Miscellaneous](#miscellaneous)

### Cross-Site Scripting (XSS)
- [RPO that lead to information leakage in Google](http://blog.innerht.ml/rpo-gadgets/) by filedescriptor

### Brute Force
- [Web Authentication Endpoint Credentials Brute-Force Vulnerability](https://hackerone.com/reports/127844) by Arne Swinnen

### SQL Injection
- [SQL injection in Wordpress Plugin Huge IT Video Gallery in Uber](https://hackerone.com/reports/125932) by glc

### Stealing Access Token
- [Facebook Access Token Stolen](https://whitton.io/articles/stealing-facebook-access-tokens-with-a-double-submit/) by Jack Whitton - 

#### Google oauth bypass

- [Bypassing Google Authentication on Periscope's Administration Panel](https://whitton.io/articles/bypassing-google-authentication-on-periscopes-admin-panel/) By Jack Whitton

### CSRF

- [Messenger.com CSRF that show you the steps when you check for CSRF](https://whitton.io/articles/messenger-site-wide-csrf/) by Jack Whitton 

### Remote Code Execution
- [JDWP Remote Code Execution in PayPal](https://www.vulnerability-lab.com/get_content.php?id=1474) by Milan A Solanki

####  Deserialization
  - [Java Deserialization in manager.paypal.com](http://artsploit.blogspot.hk/2016/01/paypal-rce.html) by Michael Stepankin
  - [Instagram's Million Dollar Bug](http://www.exfiltrated.com/research-Instagram-RCE.php) by Wesley Wineberg 
  - [(Ruby Cookie Deserialization RCE on facebooksearch.algolia.com](https://hackerone.com/reports/134321) by Michiel Prins (michiel)
  - [Java deserialization](https://seanmelia.wordpress.com/2016/07/22/exploiting-java-deserialization-via-jboss/) by meals

####  Image Tragick
  - [Exploiting ImageMagick to get RCE on Polyvore (Yahoo Acquisition)](http://nahamsec.com/exploiting-imagemagick-on-yahoo/) by NaHamSec

### Direct Object Reference (IDOR)
- [Trello bug bounty: The websocket receives data when a public company creates a team visible board](https://hethical.io/trello-bug-bounty-the-websocket-receives-data-when-a-public-company-creates-a-team-visible-board/) by Florian Courtial 

### XXE
- [How we got read access on Google’s production servers](https://blog.detectify.com/2014/04/11/how-we-got-read-access-on-googles-production-servers/) by  detectify

### Unrestricted File Upload
- [File Upload XSS in image uploading of App in mopub](https://hackerone.com/reports/97672) by vijay kumar 

### Server Side Request Forgery (SSRF)
- [ESEA Server-Side Request Forgery and Querying AWS Meta Data](http://buer.haus/2016/04/18/esea-server-side-request-forgery-and-querying-aws-meta-data/) by Brett Buerhaus

### Race Condition

- [Race conditions on Facebook, DigitalOcean and others (fixed)](http://josipfranjkovic.blogspot.hk/2015/04/race-conditions-on-facebook.html) by Josip Franjković

### Business Logic Flaw
- [How I Could Steal Money from Instagram, Google and Microsoft](https://www.arneswinnen.net/2016/07/how-i-could-steal-money-from-instagram-google-and-microsoft/) by Arne Swinnen

### Authentication Bypass
- [OneLogin authentication bypass on WordPress sites via XMLRPC in Uber](https://hackerone.com/reports/138869) by Jouko Pynnönen (jouko)

### HTTP Header Injection
- [Twitter Overflow Trilogy in Twitter](https://blog.innerht.ml/overflow-trilogy/) by filedescriptor

### Subdomain Takeover

- [Hijacking tons of Instapage expired users Domains & Subdomains](http://www.geekboy.ninja/blog/hijacking-tons-of-instapage-expired-users-domains-subdomains/) by geekboy

## XSSI
- [Plain Text Reading by XSSI](http://balpha.de/2013/02/plain-text-considered-harmful-a-cross-domain-exploit/)

## Email Related
- [This domain is my domain - G Suite A record vulnerability](http://blog.pentestnepal.tech/post/156959105292/this-domain-is-my-domain-g-suite-a-record)

## Money Stealing
- [Round error issue -> produce money for free in Bitcoin Site](https://hackerone.com/reports/176461) by 4lemon

## 2017 Local File Inclusio
- [Disclosure Local File Inclusion by Symlink](https://hackerone.com/reports/213558)

## Miscellaneous
- [SAML Pen Test Good Paper](http://research.aurainfosec.io/bypassing-saml20-SSO/)
