---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---

En **M12**, nuestro objetivo es **fortalecer la seguridad** de los sistemas de servidores de nuestros compañeros. 
A través de análisis y pruebas, buscamos identificar vulnerabilidades y mejorar la protección de datos, 
asegurando un entorno digital más seguro para todos. ¡Únete a nosotros en esta misión de ciberseguridad!


Grupos	IPs	Servicios
Grupo A	192.168.1.1	HTTP, SSH
Grupo B	192.168.1.2	FTP, DNS
Grupo C	192.168.1.3	SMTP, HTTPS
2. Listas con Viñetas

Utiliza listas para destacar cada elemento.

    **Grupo: 1**

    IPs:
        192.168.1.1 - DNS
            Puertos: 
                22, 53
        
        192.168.1.2 - Apache
            Puertos:
                
        192.168.1.3 - AD
        Puertos: 
    
    53: domain
    80: http
    88: kerberos-sec
    135: msrpc
    139: netbios-ssn
    389: ldap
    445: microsoft-ds
    464: kpasswd5
    593: http-rpc-epmap
    636: ldapssl
    3268: globalcatLDAP
    3269: globalcatLDAPssl
    3389: ms-wbt-server
    5985: wsman
    9389: adws
    47001: winrm
    49664-49680, 49692, 49790: puertos dinámicos


    Servicios:
        SSh, Bind9
        Apache, DNS
        SMTP, HTTPS

3. Secciones con Encabezados

Divide la información en secciones con encabezados claros.
Grupos

    Grupo A
    Grupo B
    Grupo C

IPs

    192.168.1.1
    192.168.1.2
    192.168.1.3

Servicios

    HTTP, SSH
    FTP, DNS
    SMTP, HTTPS
