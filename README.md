# Configuracion Basica de Samba

### Que es samba?

Samba es una implementación libre del protocolo de archivos compartidos de Microsoft Windows (antiguamente llamado SMB, renombrado posteriormente a CIFS) para sistemas de tipo UNIX.
De esta forma, es posible que computadoras con GNU/Linux,Mac OS X o Unix en general se vean como servidores o actúen como clientes en redes de Windows.
Samba también permite validar usuarios haciendo de Controlador Principal de Dominio (PDC), como miembro de dominio e incluso como un dominio Active Directory para redes basadas en Windows;
aparte de ser capaz de servir colas de impresión, directorios compartidos y autentificar con su propio archivo de usuarios.


### La configuracion incluye:

- Configuracion global
- Configuracion de usuarios invitados (guest)
- Configuracion de usuarios con contraseña (user)

### Notas importantes:

- Debes tener instalado Samba.

- Para que la configuracion funcione debe de estar en el directorio correspondiente "/etc/samba/smb.conf"

Puede consultar configuraciones alternativas y cambios en https://wiki.samba.org/index.php/Setting_up_Samba_as_a_Standalone_Server
