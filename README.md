### Project only accepting patches
This project is not actively developed but *will* accept Pull Requests.

<h1 align="center">
  <a href=https://www.archlinux.org/>Archlinux</a> Ultimate Installer
</h1>
<h4 align="center">Installation & Configuration of archlinux has never been much easier!</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/helmuthdu/aui?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/helmuthdu/aui?color=violet&style=for-the-badge">
  <img src="https://img.shields.io/github/stars/helmuthdu/aui?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/helmuthdu/aui?color=teal&style=for-the-badge">
</p>


## Notas
ATENÇAO >>> SOMENTE PARA TESTES 

********************************************************************
- NAO USE EM HD COM CONTEUDOS IMPORTANTES.
- NAO DEIXE MAIS NENHUM OUTRO HD CONECTADO 
- PREFERENCIA TESTAR EM MAQUINA VIRTUAL
- lilo AINDA NAO TRABALHADO E NAO TESTADO
********************************************************************

## Prerequisites

- Uma internet ativa
- Logado como root

## Obtaining The Repository
### With git
- Obtenha a lista de pacotes e instale git: `pacman -Sy git`
- Obtenha o script: `git clone git://github.com/rcdenes777/aui `
 

## How to use
Entre na pasta aui:
#cd aui

Mude para executavel:
#chmod +x fifo.sh

Execute o script
#./fifo.sh

## Pacotes Instalado com o SCRIPT fifo:
- base linux linux-headers
- linux-firmware nano bash-completion usbutils
- base-devel parted btrfs-progs f2fs-tools net-tools
- intel-ucode ou adm-ucode
- grub os-prober grub-btrfs snapper grub-customizer grub-theme-vimix
- refind-efi os-prober
- efibootmgr dosfstools


## Features
### FIFO SCRIPT
- Configure keymap
- Select editor
- Automatic configure mirrorlist
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password


## Thank helmuthdu
If you like my work, please consider a small Paypal donation at helmuthdu@gmail.com :)

## License :scroll:
This project is licenced under the GNU General Public License V3. For more information, see the `LICENSE` file or visit https://www.gnu.org/licenses/gpl-3.0.en.html.
