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

**Servicios y sus significados**

| **Puerto** | **Servicio**       | **Descripción**                                                                 |
|------------|--------------------|---------------------------------------------------------------------------------|
| 21         | FTP                | Protocolo de transferencia de archivos, utilizado para subir y bajar archivos. |
| 22         | SSH                | Protocolo seguro para acceder a sistemas de forma remota y transferir archivos. |
| 53         | DNS                | Sistema de nombres de dominio, traduce nombres de dominio a direcciones IP.    |
| 80         | HTTP               | Protocolo de transferencia de hipertexto, utilizado para la navegación web.     |
| 88         | Kerberos-sec       | Protocolo de autenticación que permite la comunicación segura en redes.         |
| 135        | MSRPC              | Protocolo de llamada a procedimiento remoto de Microsoft, usado para servicios.  |
| 139        | NetBIOS-SSN       | Protocolo para compartir archivos e impresoras en redes locales.                |
| 389        | LDAP               | Protocolo de acceso ligero a directorios, utilizado para acceder a servicios de directorio. |
| 443        | HTTPS              | HTTP seguro, utilizado para la navegación web segura.                           |
| 445        | Microsoft-DS       | Protocolo para compartir archivos e impresoras en redes Windows.                |
| 464        | Kpasswd5           | Protocolo para cambiar contraseñas en Kerberos.                                 |
| 593        | HTTP-RPC-EPMAP     | Protocolo para la comunicación de servicios RPC sobre HTTP.                     |
| 636        | LDAPSSL            | LDAP sobre SSL, versión segura del protocolo LDAP.                              |
| 3268       | GlobalCatLDAP      | Protocolo para acceder al catálogo global de Active Directory.                  |
| 3269       | GlobalCatLDAPSSL   | Versión segura del acceso al catálogo global de Active Directory.               |
| 3387       | Backroomnet        | Protocolo utilizado para la comunicación en ciertos sistemas.                   |
| 3389       | MS-WBT-Server      | Protocolo de escritorio remoto de Microsoft (RDP).                              |
| 5357       | WSDAPI             | Protocolo para servicios web en dispositivos.                                    |
| 5504       | FCP-CICS-GW1       | Protocolo utilizado para la comunicación en sistemas mainframe.                 |
| 5985       | WSMan              | Protocolo para la gestión de sistemas a través de web services.                 |
| 9389       | ADWS               | Servicios web de Active Directory, utilizado para acceder a directorios.       |
| 47001      | WinRM              | Protocolo de gestión remota de Windows.                                         |
| 8080       | HTTP-Proxy         | Puerto alternativo para el tráfico HTTP, a menudo utilizado para proxies.      |


**Gruipo 1**

        IP: 10.45.1.1
    Puertos Abiertos:
    
    22: ssh - OpenSSH 9.2p1 Debian
    53: domain - ISC BIND 9.18.28-1~deb12u2

    OS: Linux

        
        IP: 10.45.1.2
    Puertos Abiertos:
    
    22: ssh - OpenSSH 8.9p1 Ubuntu
    80: http - Apache httpd 2.4.52
    443: ssl/http - Apache httpd 2.4.52
    8080: http - Apache httpd 2.4.52

    OS: Linux

                
       IP: 10.45.1.3
    Puertos Abiertos:
    
    53: domain - Simple DNS Plus
    80: http - Microsoft IIS httpd 10.0
    88: kerberos-sec - Microsoft Windows Kerberos
    135: msrpc - Microsoft Windows RPC
    139: netbios-ssn - Microsoft Windows netbios-ssn
    389: ldap - Microsoft Windows Active Directory LDAP
    445: microsoft-ds - ?
    464: kpasswd5 - ?
    593: ncacn_http - Microsoft Windows RPC over HTTP 1.0
    636: tcpwrapped - 
    3268: ldap - Microsoft Windows Active Directory LDAP
    3269: tcpwrapped - 
    3389: ms-wbt-server - Microsoft Terminal Services
    5985: http - Microsoft HTTPAPI httpd 2.0

    OS: Windows


   
**Grupo 2**

       IP: 10.45.2.3
    Puertos Abiertos:
    
    21: ftp - ProFTPD (FtpMonFrague)
    22: ssh - OpenSSH 9.6p1 Ubuntu
    80: http - Apache httpd 2.4.58 (Ubuntu)
    443: ssl/http - Apache httpd 2.4.58 (Ubuntu)
    8080: http - Apache httpd 2.4.58 (Ubuntu)

    OS: Linux

               
        
       IP: 10.45.2.11
    Puertos Abiertos:
    
    53: domain - ISC BIND 9.18.28-1~deb12u2 (Debian Linux)

    OS: Linux

                
        IP: 10.45.2.
    pendiente de escaneo

**Grupo 3**

       IP: 10.45.3.10
    Puertos Abiertos:
    
    53: domain - Simple DNS Plus
    80: http - Microsoft IIS httpd 10.0
    88: kerberos-sec - Microsoft Windows Kerberos
    135: msrpc - Microsoft Windows RPC
    139: netbios-ssn - Microsoft Windows netbios-ssn
    389: ldap - Microsoft Windows Active Directory LDAP
    445: microsoft-ds - ?
    464: kpasswd5 - ?
    593: ncacn_http - Microsoft Windows RPC over HTTP 1.0
    636: tcpwrapped - ?
    3268: ldap - Microsoft Windows Active Directory LDAP
    3269: tcpwrapped - ?
    3389: ms-wbt-server - Microsoft Terminal Services
    5357: http - Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
    5985: http - Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)

        OS: Windows

       
        
      IP: 10.45.3.20
    Puertos Abiertos:
    
    53: domain - ISC BIND 9.18.28-1~deb12u2 (Debian Linux)

        OS: Linux



        IP: 10.45.3.30
    Puertos Abiertos:
    
    22: ssh - OpenSSH 8.9p1 Ubuntu
    80: http - Apache httpd 2.4.52
    443: http - Apache httpd 2.4.52
    8080: http - Apache httpd 2.4.52

        OS: Linux



**Grupo 4**

    pendiente de escaneo

    
**Grupo 5**

       IP: 10.45.2.3
    Puertos Abiertos:
    
    21: ftp - ProFTPD (FtpMonFrague)
    22: ssh - OpenSSH 9.6p1 Ubuntu
    80: http - Apache httpd 2.4.58 (Ubuntu)
    443: ssl/http - Apache httpd 2.4.58 (Ubuntu)
    8080: http - Apache httpd 2.4.58 (Ubuntu)

    OS: Linux

               
        
       IP: 10.45.2.11
    Puertos Abiertos:
    
    53: domain - ISC BIND 9.18.28-1~deb12u2 (Debian Linux)

    OS: Linux

                
        IP: 10.45.2.
    Puertos Abiertos:
    
    

    OS: Windows

**Grupo 6**

      IP: 10.45.6.3
    Puertos Abiertos:
    
    135: msrpc - Microsoft Windows RPC
    5040: unknown - (no service detected)

    OS: Windows

**Grupo 7**

        IP: 10.45.7.1
    Puertos Abiertos:

    53: domain - DNS
    80: http - Apache
    88: kerberos-sec - Kerberos
    135: msrpc - Microsoft Windows RPC
    139: netbios-ssn - NetBIOS Session Service
    389: ldap - LDAP
    445: microsoft-ds - SMB
    464: kpasswd5 - Kerberos Password
    593: http-rpc-epmap - RPC over HTTP
    636: ldapssl - LDAP over SSL
    3268: globalcatLDAP - Global Catalog LDAP
    3269: globalcatLDAPssl - Global Catalog LDAP over SSL
    3389: ms-wbt-server - RDP
    5357: wsdapi - Web Services for Devices API
    5985: wsman - Windows Remote Management
    9389: adws - Active Directory Web Services
    49667: unknown
    49675: unknown
    49676: unknown
    49677: unknown
    49681: unknown
    49693: unknown
    49810: unknown


        IP: 10.45.7.2
    Puertos Abiertos:

    21: ftp - Protocolo de transferencia de archivos
    22: ssh - Secure Shell
    80: http - Protocolo de transferencia de hipertexto
    443: https - HTTP seguro
    8080: http-proxy - Proxy HTTP

MAC Address: 08:00:27:9F:A8:A6




**Grupo 8**

        IP: 10.45.8.1

    Puertos Abiertos:
        21: ftp
        22: ssh
        53: domain (DNS)
    Estado: Up
    Puertos Cerrados: 65,532

        IP: 10.45.8.2

    Puertos Abiertos:
        53: domain (DNS)
        80: http
        88: kerberos-sec
        135: msrpc
        139: netbios-ssn
        389: ldap
        443: https
        445: microsoft-ds
        464: kpasswd5
        593: http-rpc-epmap
        636: ldapssl
        3268: globalcatLDAP
        3269: globalcatLDAPssl
        3387: backroomnet
        3389: ms-wbt-server
        5357: wsdapi
        5504: fcp-cics-gw1
        5985: wsman
        9389: adws
        47001: winrm
    Estado: Up
    Puertos Cerrados: 58,143
    Puertos Filtrados: 7,358

                IP: 10.45.8.4

            Puertos Abiertos:
        80: http
        8080: http-proxy
            Estado: Up
            Puertos Cerrados: 65,533



