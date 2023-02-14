﻿nopCommerce: free and open-source eCommerce solution[![Build Status](https://travis-ci.com/nopSolutions/nopCommerce.svg?branch=develop)](https://travis-ci.com/nopSolutions/nopCommerce)
===========

[nopCommerce](https://www.nopcommerce.com/?utm_source=github&utm_medium=content&utm_campaign=homepage) is the best open-source eCommerce shopping cart solution. nopCommerce is free, and it is the most popular ASP.NET eCommerce platform.

![nopCommerce demo](https://www.nopcommerce.com/images/github/responsive_devices_codeplex.png#v1)

The product is being developed and supported by the professional team since 2008.

nopCommerce has been downloaded more than 3,000,000 times.

The active developer community has more than 250,000 members.

nopCommerce runs on ASP.NET Core 5 with an MS SQL 2012 (or higher) backend database.

nopCommerce is cross-platform, and you can run it on Windows, Linux, or Mac.

nopCommerce supports Docker and MySQL out of the box, so you can easily run nopCommerce on a Linux machine.

nopCommerce supports PostgreSQL database.

nopCommerce fully supports web farms. You can read more about it [here](https://docs.nopcommerce.com/en/developer/tutorials/web-farms.html?utm_source=github&utm_medium=referral&utm_campaign=documentation&utm_content=text).  

All methods in nopCommerce are async.

nopCommerce supports multi-factor authentication out of the box.

![Logo](https://www.nopcommerce.com/images/github/logos.png#v2)

nopCommerce architecture follows well-known software patterns and the best security practices. The source code is fully customizable. Pluggable and clear architecture makes it easy to develop custom functionality and follow any business requirements.

Using the latest Microsoft technologies, nopCommerce provides high performance, stability, and security. nopCommerce is also fully compatible with Azure and web farms.

Clear and detailed [documentation for developers](https://docs.nopcommerce.com/developer/index.html?utm_source=github&utm_medium=referral&utm_campaign=documentation&utm_content=text) will help you start with nopCommerce easily.


### The advantages of working with nopCommerce ###

nopCommerce offers powerful [out-of-the-box features](https://www.nopcommerce.com/features?utm_source=github&utm_medium=referral&utm_campaign=features&utm_content=text) for creating an online store of any size and type.

nopCommerce is integrated with all the popular third-party services. You can find thousands of integrations on nopCommerce [Marketplace](https://www.nopcommerce.com/marketplace?utm_source=github&utm_medium=referral&utm_campaign=marketplace&utm_content=text).

Friendly members of the [nopCommerce community](https://www.nopcommerce.com/boards?utm_source=github&utm_medium=referral&utm_campaign=forum&utm_content=text) will always help with advice and share their experiences. nopCommerce core development team provides [professional support](https://www.nopcommerce.com/nopcommerce-premium-support-services?utm_source=github&utm_medium=referral&utm_campaign=premium_support&utm_content=text) within 24 hours.


## Store demo ##

Evaluate the functionality and convenience of nopCommerce as a customer and store owner.

Front End | Admin area
----|------
[![ScreenShot](https://www.nopcommerce.com/images/github/public-demo.png#v1)](https://frontend.nopcommerce.com?utm_source=github&utm_medium=referral&utm_campaign=demo_store&utm_content=button) | [![ScreenShot](https://www.nopcommerce.com/images/github/admin-demo.png#v1)](https://admin-demo.nopcommerce.com/admin?utm_source=github&utm_medium=referral&utm_campaign=demo_store&utm_content=button)


### nopCommerce resources ###

nopCommerce official site: [https://www.nopcommerce.com](https://www.nopcommerce.com/?utm_source=github&utm_medium=referral&utm_campaign=homepage&utm_content=links)

* [Demo store](https://www.nopcommerce.com/demo?utm_source=github&utm_medium=referral&utm_campaign=demo_store&utm_content=links)
* [Download nopCommerce](https://www.nopcommerce.com/download-nopcommerce?utm_source=github&utm_medium=referral&utm_campaign=download_nop&utm_content=links)
* [Feature list](https://www.nopcommerce.com/features?utm_source=github&utm_medium=referral&utm_campaign=features&utm_content=links)
* [nopCommerce documentation](https://docs.nopcommerce.com?utm_source=github&utm_medium=referral&utm_campaign=documentation&utm_content=links)
* [Community forums](https://www.nopcommerce.com/boards?utm_source=github&utm_medium=referral&utm_campaign=forum&utm_content=links)
* [Premium support services](https://www.nopcommerce.com/nopcommerce-premium-support-services?utm_source=github&utm_medium=referral&utm_campaign=premium_support&utm_content=links)
* [Certified developer program](https://www.nopcommerce.com/certified-developer-program?utm_source=github&utm_medium=referral&utm_campaign=certified_developer&utm_content=links)
* [nopCommerce partners](https://www.nopcommerce.com/partners?utm_source=github&utm_medium=referral&utm_campaign=solution_partners&utm_content=links)

nopCommerce YouTube: [The Architecture behind the nopCommerce eCommerce Platform](https://www.youtube.com/watch?v=6gLbizzSA9o&list=PLnL_aDfmRHwtJmzeA7SxrpH3-XDY2ue0a)


### Earn with nopCommerce ###

60,000 stores worldwide are powered by nopCommerce, and 10,000 new stores open every year. nopCommerce [solution partners’ directory](https://www.nopcommerce.com/partners?utm_source=github&utm_medium=referral&utm_campaign=solution_partners&utm_content=text_become_partner) gets 80,000+ page views per year from store owners who are looking for a partner to build a store from scratch, migrate from another platform, or improve and customize an existing store.

Become a solution partner of nopCommerce and get new clients – [learn more](https://www.nopcommerce.com/become-partner?utm_source=github&utm_medium=referral&utm_campaign=become-partner&utm_content=learn_more).

Create a new graphical theme or develop a new plugin or integration and sell it on the nopCommerce [Marketplace](https://www.nopcommerce.com/marketplace?utm_source=github&utm_medium=referral&utm_campaign=marketplace&utm_content=text_sell_on_marketplace).


### Contribute ###

As a free and open-source project, we are very grateful to everyone who helps us to develop nopCommerce. Please find more details about the options and bonuses for contributors at [сontribute page](https://www.nopcommerce.com/contribute?utm_source=github&utm_medium=referral&utm_campaign=contribute&utm_content=text).

### Publish ###
Potrebno je uraditi folder publish na 'bin\Release\net5.0\publish\' a zatim sadrzaje foldera uploadovati na FTP server. Iz nekog razloga, publish direktno na FTP server ne radi. Verovatno je problem u autentikaciji i nedostatku permisija korisnika nad FTP serverom.

Ena - is nopCommerce the application.

Clone the repository and publish the Nop.Web project.
Configure dataSettings if you are using an existing database. Example path yourStore\src\Presentation\Nop.Web\bin\Release\net5.0\publish\App_Data

#Setup the Ena application on the ubuntu VPS server
Publish the Nop.Web project with next parameters: 	Publish method - File System
													Deployment Mode - Self-contained
													Target Runtime - linux-x64
														
Configure dataSettings in App_Data folder if you are using an existing database. Example path yourStore\src\Presentation\Nop.Web\bin\Release\net5.0\publish\App_Data

Install nginx: sudo apt-get install nginx
Start nginx: sudo systemctl start nginx
Status of nginx: sudo systemctl status nginx

Change default file on /etc/nginx/sites-available.
Example default file:
		
				# Default server configuration
				#
				server {
					listen 80;
					listen [::]:80;

					server_name   yourDomain;

					location / {
						proxy_pass         http://localhost:5000;
						proxy_http_version 1.1;
						proxy_set_header   Upgrade $http_upgrade;
						proxy_set_header   Connection keep-alive;
						proxy_set_header   Host $host;
						proxy_cache_bypass $http_upgrade;
						proxy_set_header   X-Forwarded-For $proxy_add_x_forwarded_for;
						proxy_set_header   X-Forwarded-Proto $scheme;
					}
				}

Create folder for your project: mkdir /var/www/yourFolder	
Upload the published project to /var/www/yourFolder.
Create bin folder: sudo mkdir var/www/yourFolder/bin
Create logs folder: sudo mkdir var/www/yourFolder/logs
Add permissions:
		sudo chgrp -R www-data var/www/yourFolder/
		sudo chown -R www-data var/www/yourFolder/
		
Create service for your application on the path /etc/systemd/system/yourService.service
Example yourService file:
		
				[Unit]
				Description=Example nopCommerce app running on Xubuntu

				[Service]
				WorkingDirectory=/var/www/nopCommerce
				ExecStart=/usr/bin/dotnet /var/www/nopCommerce/Nop.Web.dll
				Restart=always
				# Restart service after 10 seconds if the dotnet service crashes:
				RestartSec=10
				KillSignal=SIGINT
				SyslogIdentifier=nopCommerce-example
				User=www-data
				Environment=ASPNETCORE_ENVIRONMENT=Production
				Environment=DOTNET_PRINT_TELEMETRY_MESSAGE=false

				[Install]
				WantedBy=multi-user.target
				
Start the service: sudo systemctl start yourService.service
Status of your service: sudo systemctl status yourService.service
Restart nginx: sudo systemctl restart nginx
	
#Using SSL Certificate
Install Certbot: sudo apt-get install python3-certbot-nginx
Communicate with Let's Encrypt and complete the SSL binding: sudo certbot --nginx -d yourDomain
When binding is finished, in the console should be a written path of the certificate and the associated key and you should save them.
Create a config file for certificate: sudo nano /etc/nginx/snippets/certificateConfiguration.conf
Within this file, set the ssl_certificate directive to your certificate file and the ssl_certificate_key to the associated key. 
This will look like the following:
		ssl_certificate savedPathOfCertificate/nameOfCertificate.crt;
		ssl_certificate_key savedPathOfCertificateKey/nameOfCertificateKey.key (nameOfCertificateKey.pem, etc...)
Create ssl-params.conf: sudo nano /etc/nginx/snippets/ssl-params.conf
Add the following into your ssl-params.conf snippet file:
	
		ssl_protocols TLSv1.3;
		ssl_prefer_server_ciphers on;
		ssl_dhparam /etc/nginx/dhparam.pem; 
		ssl_ciphers EECDH+AESGCM:EDH+AESGCM;
		ssl_ecdh_curve secp384r1;
		ssl_session_timeout  10m;
		ssl_session_cache shared:SSL:10m;
		ssl_session_tickets off;
		ssl_stapling on;
		ssl_stapling_verify on;
		resolver 8.8.8.8 8.8.4.4 valid=300s;
		resolver_timeout 5s;
		add_header X-Frame-Options DENY;
		add_header X-Content-Type-Options nosniff;
		add_header X-XSS-Protection "1; mode=block";
Change default file to:
			# Default server configuration
			#
			server {
				listen 443 ssl;
				listen [::]:443 ssl;
				
				include snippets/self-signed.conf;
				include snippets/ssl-params.conf;

				server_name   yourDomain;

				location / {
				  proxy_pass         https://localhost:5001;
				  proxy_http_version 1.1;
				  proxy_set_header   Upgrade $http_upgrade;
				  proxy_set_header   Connection keep-alive;
				  proxy_set_header   Host $host;
				  proxy_cache_bypass $http_upgrade;
				  proxy_set_header   X-Forwarded-For $proxy_add_x_forwarded_for;
				  proxy_set_header   X-Forwarded-Proto $scheme;
				}
			}

			server {
				listen 80;
				listen [::]:80;

				server_name yourDomain;

				return 302 https://$server_name$request_uri;
			}
Change param "UseHttpXForwardedProto" to "true" in /var/www/yourFolder/App_Data/appsettings.json.
Restart your service: sudo systemctl restart yourService.service.
Open your website in the administration mode and open Stores in the Configuration section.
Click on Edit for the store that you want to use SSL for.
Change the store URL from HTTP to HTTPS and tick the "SSL enabled" checkbox.
