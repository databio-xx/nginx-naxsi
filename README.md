# nginx-naxsi
Official NGINX compiled with NAXSI deb package

This deb package is based on the official nginx:mainline source code and compiled with the same ./configure options from NGINX deb package for ubuntu with the addition of --add-module=naxsi.

NAXSI is a WAF module for [NGINX](http://nginx.org/) Anti [XSS](https://www.owasp.org/index.php/Cross-site_Scripting_%28XSS%29) & [SQL Injection](https://www.owasp.org/index.php/SQL_injection). This module is createad NBS System's [NAXSI module](https://github.com/nbs-system/naxsi)
