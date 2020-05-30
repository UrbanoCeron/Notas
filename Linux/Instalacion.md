# Instalar maven

```sh
sudo apt install maven
```

# Instalación para SpringTools

[Link para descargar SpringTools](https://spring.io/tools)

```sh
cd Downloads
sudo mv spring-tool-suite-4-4.6.2.RELEASE-e4.15.0-linux.gtk.x86_64.tar.gz /opt/
cd /opt/
sudo tar zxvf spring-tool-suite-4-4.6.2.RELEASE-e4.15.0-linux.gtk.x86_64.tar.gz
sudo ln -s /opt/sts-4.6.2.RELEASE/ /usr/local/bin/sts
sudo nano /usr/share/applications/stsLauncher.desktop
```
Nos abre el editor nano y escribimos el siguiente código

```
[Desktop Entry]
Name=Spring Tool Suite
Comment=Spring Tool Suite 4.6.2
Exec=/opt/sts-4.6.2.RELEASE/SpringToolSuite4
Icon=/opt/sts-4.6.2.RELEASE/icon.xpm
StartupNotify=true
Terminal=false
Type=Application
Categories=Development;IDE;Java;
```

# Instalar SmartGit

Para instalar smartgit en Linux descargamos el archivo .deb [aquí](https://www.syntevo.com/smartgit/)

```sh
sudo apt install ./<file>.deb
```

