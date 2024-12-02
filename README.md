[![Stars](https://img.shields.io/github/stars/MrAhmalo/pterodactyl-themes)](#) [![Last commit](https://img.shields.io/github/last-commit/MrAhmalo/pterodactyl-themes)](#)

## pterodactyl-themes
### Install pterodactyl themes the casual way. Ideal for panels running with docker.

<table>
<tr>
<td><img src="https://www.pngall.com/wp-content/uploads/8/Red-Warning-PNG-Free-Download.png" width="50"></td>
<td align="center" bgcolor="#FFFF00">

## WARNING
  
**This tool is currently under active development and should currently not be used!**

</td>
<td><img src="https://www.pngall.com/wp-content/uploads/8/Red-Warning-PNG-Free-Download.png" width="50"></td>
</tr>
</table>

## How to install the first time 
Only execute these commands when installing for the first time!

1. Open a new terminal for the pterodactyl panel
   
   Replace "pterodactyl-panel" with your docker image name or id. (See the name & id with ```sudo docker ps```)
   ```shell
   sudo docker exec -it pterodactyl-panel sh
   ```

3. Inside the new terminal, execute the following commands
   ```shell
   apk update && apk add git curl
   curl -o install_script.sh https://raw.githubusercontent.com/MrAhmalo/pterodactyl-themes/refs/heads/main/install_theme.sh
   chmod +x install_script.sh
   ./install_script.sh
   ```
