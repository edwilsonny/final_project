# final_project
Contains README file detailing Final Project

## Table of Contents

- [Summary](#Summary)
- [Table of Contents](#table-of-contents)
- [SSH IP and Port](#SSH-IP-and-Port)
- [UserID](#User-ID)
- [Prerequisites](#Prerequisites)
- [URL for Application](#URL-for-Application)

## Summary

Spun up an instance of Linux on Azure Cloud Platform and made the following configuarions:

- Updated all packages to current releases.
- Modified SSH port to listen on port 2200.
- Configured Firewall to only allow connections on ports - 80, 2200, 123.
- Created an account (grader) and created SSH key pair to allow passwordless access.
- User (grader) was given sudo access.
- Changed Local Timezone to UTC.
- Removed ability to logon remotely with root.
- Removed ability to logon with a password.
- Installed Apache2 listening on port 80.
- Installed Postgres DB.

Ported the Sport-Catalog application and installed in /var/www/catalog using wsgi to serve it up.
     
     
## SSH IP and Port

137.117.44.193:2200

## User ID

grader

## Prerequisites

* Postgress
* Apache2
* Mod_wsgi

* asn1crypto==0.24.0
* certifi==2019.9.11
* chardet==3.0.4
* Click==7.0
* configparser==3.5.0b2
* cryptography==2.3
* docopt==0.6.2
* entrypoints==0.2.3.post3
* enum34==1.1.6
* Flask==1.1.1
* httplib2==0.13.1
* idna==2.8
* ipaddress==1.0.17
* itsdangerous==1.1.0
* Jinja2==2.10.1
* keyring==15.1.0
* keyrings.alt==3.1
* MarkupSafe==1.1.1
* oauth2client==4.1.3
* pipreqs==0.4.9
* pyasn1==0.4.7
* pyasn1-modules==0.2.6
* pycrypto==2.6.1
* PyGObject==3.30.1
* pyxdg==0.25
* requests==2.22.0
* rsa==4.0
* SecretStorage==2.3.1
* six==1.12.0
* SQLAlchemy==1.3.8
* urllib3==1.25.6
* Werkzeug==0.15.6
* yarg==0.1.9


## URL for Application

```
http://www.137.117.44.193.xip.io/
```


[(Back to TOC)](#table-of-contents)
