- 👋 Hola, soy @whitehax0r tambien conocido como (razr2312) en Twitter.
- 💞️ Estoy buscando colaborar en la Comunidad de PS4 Linux y otras cosas de interes en comun.
- 📫 Como me puedes contactar, al final de este post lo sabras.
<!---
whitehax0r/whitehax0r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# ArchLinux-PS4v2

Esta es una compilacion actualizada de Arch Linux con algunos cambios personales mas relacionadas a la interfaz grafica para que se vea mejor con algunos emuladores.

![desktop2](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/2ba4c9d407440a07d327011caef73b2786445ff3/Desktop.png)

# Novedades

## Todo ha sido actualizado hasta Agosto 23/2022

- Descarga de paquetes paralelas activada.
- Se actualizo los Drivers the PS4 a la ultima version estable de MESA, libdrm y xf86-video-amdgpu. (Compilados por mi)
- LightDM con autologin habilitado.
- Neofetch - Muestra informacion general sobre el sistema.
- XFCE - Entorno de Escritorio.
- Steam - El destino definitivo para jugar, discutir y crear juegos.
- Lutris - Juega todos tus juegos en Linux. Lutris es una plataforma de juegos de código abierto para Linux.
- Soporte the sistema de ficheso ExFat y NTFS.
- Bluez - Para poder conectar el control de PS3/PS4/PS5.
- Blueberry - Interfaz bluetooth grafica compatible con XFCE/GTK.
- Duckstation - El mejor emulador de PSX.
- Flatpak - Tecnología de próxima generación para construir y distribuir aplicaciones de escritorio en Linux.
- Dolphin emulator - Emulador de Nintengo Wii y Gamecube.
- Nano - Editor de texto.
- Chromium - El mejor navegador web.
- Powerlevel10k - Terminal ZSH.
- PCSX2 - Emulador de PS2 con soporte vulkan.
- Yabaouze - Emulador de Sega Dreamcast.
- Hacknerdfonts - Fuente de letras compatible con los iconos de la terminal ZSH.
- RetroArch - Emulador multiplataforma.
- Minecraft Java - Porque es divertido. :pick:
- LSD - Programa LS mejorado.
- BAT - Programa CAT mejorado.
- VLC - Reproductor multimedia de video y audio.
- Spotify - Reproductor de musica online.
- Yay - Envoltorio pacman y ayudante AUR escrito en GO.
- Zip - Comprime archivos con la extension .zip
- Unzip - Descomprime archivos con la extension .zip
- P7zip - Compatibilidad con 7zip de la línea de comandos para Linux.
- HTOP - Gestiona procesos y otras cosas mas.
- FeralGameMode - Es un daemon/lib combo para Linux que permite a los juegos solicitar que un conjunto de optimizaciones se aplique temporalmente al sistema operativo host y/o a un proceso de juego.
- WineStaging - Wine es una capa de compatibilidad capaz de ejecutar aplicaciones de Windows en varios sistemas operativos compatibles con POSIX, como Linux, macOS y BSD.
- Wine GE on Lutris -  WINE basado en un fork del más reciente repositorio experimental de WINE de Proton Steam. Esto está destinado a ser utilizado con juegos que no son de Steam fuera de Steam.
- ProtonVPN - Cliente VPN the Alta-velocidad que protege tu seguridad.

# Requerimientos obligatorios
- Un cerebro xD y mucha paciencia.
- USB|HDD|SDD 3.0
- USB Hub para que conectes multiples dispositivos USB. (opcional)
- USB o mouse Bluetooth y teclado.

# El Hardware de mi PS4

- PS4 Slim
- Firmware 9.00
- Modelo CUH-2115B.
- SouthBridge Baikal con Liverpool.

# Novedades del Kernel
Estos Kernels estan basados en LTS(LongTerm Support) version 5.4.210 fecha de lanzamiento Agosto 11 2022. Significa que los maintainers proporcionarán correcciones de errores para esta revisión del kernel durante un período de tiempo mucho más largo.
- Soporte OverlayFS.
- Soporte SquashFS.
- Soporte TUN/TAP. (Funciona con el cliente VPN de tu preferencia)

## Si tienes el mismo Hardware de PS4, puedes usar los siguientes archivos:

- [bootargs.txt](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bootargs.txt) o [Download here](https://mega.nz/file/2qBCTJpR#CTD_nQOLFsrBMcau-KS6QitasbuVAXx_PPN22Wk2qoo) MD5 >__C84AD779CE76762C04CBF80E420E324D__
- [initramfs.cpio.gz](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/c01e7d6162ad8029748b408f930f5b9952734418/initramfs.cpio.gz)
- 4.19.255 [Baikal 1.6 Ghz](https://mega.nz/file/2mxRRZwT#TgkW1_QBiI24QKZerIYHoYebdpjEPvClXOi-ZYz61DQ)
- 4.19.255 [Baikal 1.9 Ghz](https://mega.nz/file/LuBmDB7L#7jPfWuEgg1QM6-jgvGm1rr1cX0wT_6eSIA7ElQYybMo)
- 5.4.210 [Baikal 1.6 Ghz](https://mega.nz/file/W3gSGA6Q#Oafpe8Q7_iUCfvaoQkyiqRIeocD2_WZ1wh8Afp6_6mQ)
- 5.4.210 [Baikal 1.9 Ghz](https://mega.nz/file/zmBgWJpb#jnWJdYjcQcxnMgQVXtiOPCTJjR8irMxqh2S9rJelBPc) 
- XanMod [Baikal 1.6 Ghz](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/3766ae7a6b7f3f47b705f90e6ad4df168cf4d47e/bzImage)
- XanMod [Baikal 1.9Ghz](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/8363f7fdfc1a0a37d59430b5aedd008b0ee57cad/bzImage1.9)
- [archv2.tar.xz](https://mega.nz/file/vn5glJbB#ZWSZA7scPuyx1UkOiM_UW7NoUxxMc_L3pJGiUWKbmRI) MD5 >__8bbd77efb78250a8d5eba6cd0201bb54__
- ⚠️ No olvides renombrar el archivo archv2.tar.xz a psxitarch.tar.xz ⚠️ 
- ⚠️ No olvides renombrar estos archivos Kernel Baikal a bzImage ⚠️ 

## Si tienes una version de PS4 Fat o PS4 Pro puedes probar estos Kernels:
- 5.4.210 [Aeolia 1.6 Ghz](https://mega.nz/file/fvgUCZpB#CEcxr2plEF-zSAy3XLpMjEJH4Hq0dxEeTOlx-JvGti4)
- 5.4.210 [Aeolia 1.9 Ghz](https://mega.nz/file/rjBgFaRJ#MXc9cOAPBDsKbXXYETBFXYJUpxGVdDpRWq1XuFEfTMg)
- 5.4.210 [Belize 1.6 Ghz](https://mega.nz/file/DyAmVZ5Y#xd8MbuExpYM19rwsc0iwru7iIkrZpyelnFTJl_jucOo)
- 5.4.210 [Belize 1.9 Ghz](https://mega.nz/file/nyoFTZLA#13w00tZjVRWRGUXYWLgpmlyIJ0i4o__AWydgv1Nbq_8)
- ⚠️ No olvides renombrar estos Kernels a bzImage ⚠️ 
- ⚠️ Estos Kernels no estan probados, no tengo estos modelos de PS4, porfavor primero pruebalos si o no funcionan, hazmelo saber! ⚠️ 

# Preparando tu sistema de PS4.

- Asegurate que tienes primero el sistema operativo 9.00.
- Ve a Ajustes>Sonido y pantalla>Ajustes de salida de video>
- Resolucion cambialo a >1080p
- Opcion RGB cambialo a >Completo
- HDR cambialo a >Desactivado
- Salida de color profundo cambialo a >Desactivado
- Ve a Ajustes>Sistema>
- Desmarca la cajita "Activar enlace del dispositivo HDMI"
- Desmarca la cajita "Activar HDCP"

# Metodo de instalacion tradicional

## Prepara tu USB|HDD|SDD 3.0 disposito para ArchLinux-PS4v2

:warning: Altamente recomendado que uses un >=16GB USB 3.0 dispositivo. :warning:

- Formatea el USB|HDD|SDD 3.0 dispositivo al sistema de ficheros FAT32. Puedes utilizar este [software.](http://ridgecrop.co.uk/index.htm?guiformat.html)
- Copia y pega el bzImage, el initramfs.cpio.gz, bootargs.txt y psxitarch.tar.xz en la raiz de la USB|HDD|SDD 3.0 dispositivo.
- :warning: Si estas usando el initramfs.cpio.gz de este proyecto GitHub, el nombre de este sistema operativo deberia de ser psxitarch.tar.xz :warning:
- El total de 4 archivos en la raiz de tu dispositivo USB|HDD|SDD 3.0: bzImage, initramfs.cpio.gz, bootargs.txt y psxitarch.tar.xz.
- Luego conecta tu dispositivo USB|HDD|SDD 3.0 a tu PS4, asegurate que tu dispositivo USB|HDD|SDD 3.0 esta conectado al puerto USB que este mas cerca de la lectora de Blu-ray de tu PS4.
- Abre el Navegador web de tu PS4 y lanza el payload JB+LINUX (VRAM 1GB), puedes usar este [host.](https://sleirsgoevy.github.io/900-host/).
- Sigue las instrucciones en order para que puedas hacer Jailbreak a tu PS4.

## Primer arranque de la instalacion de ArchLinux-PS4v2

- Cuando estes en el rescueshell escribe los siguientes comandos:
>__exec install-psxitarch.sh__
- Cuando la instalacion de ArchLinux-PS4v2 termine tiene que iniciar automaticamente, en caso de que no lo hago escribe los siguientes comandos:
>__exec start-psxitarch.sh__

Si tienes un error similar a este: "mount -o ro /newroot failed" solo escribe los siguientes comandos:
>__mount -o ro /newroot__
- despues nuevamente
>__mount -o ro /newroot__
- ahora escribe esto:
>__exec start-psxitarch.sh__
- y deberia de arrancar ArchLinux-PS4v2 :)

## Pasos Post-Instalacion (en caso de que hallas seguido el Metodo Tradicional)

- Conecta tu USB|HDD|SDD 3.0 a una computadora y copia de nuevo el archivo [bootargs.txt](https://mega.nz/file/2qBCTJpR#CTD_nQOLFsrBMcau-KS6QitasbuVAXx_PPN22Wk2qoo) en la raiz de tu particion de FAT32.
- Haz Jailbreak a tu PS4 con el host de [sleirsgoevy](https://sleirsgoevy.github.io/900-host/) >> seleciona el payload JB+LINUX (VRAM 1GB).
- Tu PS4 se pondra en pantalla negra y luego estaras en el RescueShell, ahora escribe los siguientes comandos:
>__exec start-psxitarch.sh__

Si tienes un error similar a este: "mount -o ro /newroot failed" solo escribe los siguientes comandos:
>__mount -o ro /newroot__
- despues nuevamente
>__mount -o ro /newroot__
- ahora escribe esto:
>__exec start-psxitarch.sh__
- y deberia de arrancar ArchLinux-PS4v2 :)

# Metodo Recomendado

Necesitas una computadora con Linux para seguir estos pasos. Este metodo es rapido y mejor que el Metodo Tradicional.

- Conecta tu dispositivo USB|HDD|SDD 3.0 a la computadora con el Linux de tu preferencia.
- Si estas usando Ubuntu escribe el siguiente comando en la terminal sudo apt-get install gparted.
- Si estas usando Arch escribe el siguiente comando en la terminal sudo pacman -Sy gparted.
- Si estas usando Fedora escribe el siguiente comando en la terminal sudo dnf install gparted.
- Abre el programa gparted.
- Asegurate que tienes seleccionado el dispositivo USB|HDD|SDD 3.0 correcto en gparted.
- Crea una particion de 300 MB con el formato de fiches FAT32. (Esta particion no necesita nombre)
- Crea una segunda particion con el nombre de psxitarch y luego formateala al sistema de ficheros EXT4.
- Cierra gparted y monta las siguientes particiones que has creado en tu dispositivo USB|HDD|SDD 3.0, ahora estas listo para instalar ArchLinux-PS4v2.
- Copia y pega el fichero bzImage, el initramfs.cpio.gz, bootargs.txt a la raiz de la particion FAT32.
(Asumiendo que el fichero psxitarch.tar.xz esta en la carpeta "Downloads" o "Descargas") 
- Abre la Terminal y escribe los siguientes comandos:
>__sudo tar -xvJpf /home/$USER/Downloads/psxitarch.tar.xz -C /media/$USER/psxitarch__
- Una vez termine, remueve de manera segura tu dispositivo USB|HDD|SDD 3.0 de tu computadora.
- Ahora conecta tu dispositivo USB|HDD|SDD 3.0 a tu PS4, asegurate que tu dispositivo USB|HDD|SDD 3.0 esta conectado al puerto USB que esta mas cerca de la lectora de discos Blu-ray.
- Abre el navegador web de tu PS4 y haz click en el payload JB+LINUX (VRAM 1GB) o (VRAM 3GB), usa este [host](https://sleirsgoevy.github.io/900-host/). 

## Pasos Post-Instalacion (en caso de que hallas seguido el Metodo Recomendado)

- Conecta tu dispositivo USB|HDD|SDD 3.0 a tu PS4, asegurate que tu dispositivo USB|HDD|SDD 3.0 esta conectado al puerto USB que esta mas cerca de la lectora de discos Blu-ray.
- Abre el navegador web de tu PS4 y haz click en el payload JB+LINUX (VRAM 1GB) o (VRAM 3GB), usa este [host](https://sleirsgoevy.github.io/900-host/).

## Cambiando la zona horaria con fecha y hora del sistema.

La primera vez que arranques ArchLinux-PS4v2 necesitas arreglar la fecha y la hora del sistema. ⚠️Conecta tu PS4 a la red WiFi o por LAN. ⚠️

Primero revisa las zonas horarias disponibles escribiendo el siguiente comando en la terminal:
>__timedatectl list-timezones__

Por ejemplo en mi caso es: America/Tegucigalpa

Configura tu zona horaria:
>__sudo timedatectl set-timezone Zone/SubZone__

Por ejemplo en mi caso es: __sudo timedatectl set-timezone America/Tegucigalpa__

Ahora vamos a crear un enlaze simbolico para que el cambio sea permanente:
>__sudo ln -sf /usr/share/zoneinfo/Zone/SubZone /etc/localtime__

Por ejemplo en mi caso es: __sudo ln -sf /usr/share/zoneinfo/America/Tegucigalpa /etc/localtime__

Ahora vamos habilitar NTP, escribe los siguientes comandos:

>__sudo timedatectl set-ntp true__

Ahora vamos a esperar de 5~25 segundos, notaras que la fecha y la hora va cambiar a la de tu zona horaria.

# Emuladores recomendados y unos tips:

- RPCS3 - Emulador de PS3. (Puedes probar su [AppImage.](https://rpcs3.net/download))
- PCSX2 - Emulador de PS2 (Puedes probar su [AppImage.](https://pcsx2.net/downloads/#nightly-anchor))
- Yuzu - Emulador de Nintendo Switch. (Puedes probar su [AppImage.](https://yuzu-emu.org/downloads/))

Si vas a correr juegos con Wine, Swap necesita estar habilitado, solo escribe los siguientes comandos en la Terminal:

>__sudo dd if=/dev/zero of=/swapfile bs=1M count=8192 status=progress__

>__sudo chmod 0600 /swapfile__

>__sudo mkswap -U clear /swapfile__

>__sudo swapon /swapfile__

Finalmente, edita la configuracion de fstab y agrega una nueva linea al archivo: 

>__sudo nano /etc/fstab__

Copia y pega esto al final del fichero:
/swapfile none swap defaults 0 0

En tu teclado presiona CTRL + O y luego "yes" y guardaras los cambios.
Despues presiona CTRL + X para salir del menu de Nano.

Ahora puedes cerrar completamente la Terminal. 

# Problemas conocidos

No estoy seguro del porque pero cada vez que inicies Linux, tendras que desemparejar y emparejar nuevamente tu control de PS4.

# Algunas preguntas frecuentes

## Cual es la contrasena de los usuarios "sony" and "root"?
Esto puedes encontrarlo en el Desktop, vas a ver una archivo llamado Important.txt

## Tengo pantalla negra
Asegurate de que tu TV es compatible con la resolucion de 1080p, si sigues teniendo pantalla negra intenta otro monitor o TV. Tambien asegurate de que has seguido completamente la seccion de "Preparando tu sistema de PS4"

## Quiero desinstalar este sistema operativo de mi dispositivo USB|HDD|SDD 3.0
Solo formatea nuevamente tu dispositivo y listo.

## Como actualizo correctamente ArchLinux-PS4v2?
Solo escribe los siguientes comando en la Terminal:
>__sudo pacman -Syu__
- y escribe "Y" y se actualizaran todos los paquetes de Arch Linux.

Si han pasado mas de 5 meses despues de que publique este sistema operativo, escribe lo siguiente en la Terminal:
>__sudo pacman -Sy__
- despues:
>__sudo pacman -S archlinux-keyring__
- despues
>__sudo pacman -Syu__

## Puedo utilizar mi control de PS4 como un mouse de PC?
Si puedes!.

## Tengo dificultados para conectar mi control de PS4 por bluetooth?
Yo subire un video mas adelante, explicando con detalles.

## No estoy seguro de mi Hardware y modelo de PS4?
Puedes buscar [aqui](https://www.psdevwiki.com/ps4/Southbridge#Southbridge_revisions) o [aqui.](https://www.psdevwiki.com/ps4/)

## Quiero instalar MangoHUD y GOverlay.
MangoHUD:
- Descarga el paquete MangoHUDxxx.tar.gz [aqui](https://github.com/flightlessmango/MangoHud/releases)
- Extrae el paquete usando la terminal escribiendo los siguientes comandos: tar -xvf MangoHUDxxx.tar.gz
- Luego escribe en la terminal: cd MangoHud
- Luego escribe en la terminal: ./mangohud-setup.sh
- MangoHUD ya esta instalado.

GOverlay:
- Abre la terminal y escribe los siguientes comandos en la terminal: yay -S goverlay-git
- GOverlay ya esta instalado.

# Redes Sociales

- Me puedes seguir en [Twitter](https://twitter.com/razr2312)
- Me puedes seguir en [YouTube](https://www.youtube.com/user/allank2312/videos)
- Me puedes seguir en [Reddit](https://www.reddit.com/user/razr2312/)

![esta es una imagen](https://github.com/whitehax0r/ArchLinux-PS4/blob/353059a5bbb0a7f161ade53a56e374a6398d7c6a/Flag.png)
