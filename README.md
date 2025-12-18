
# 🐧 Arch CachyOS Installer

Скрипт для автоматической установки программ на Arch CachyOS

## 📦 Устанавливаемые программы:
- Notepadqq (аналог Notepad++)
- OBS Studio + медиа зависимости
- Steam + нативные рантаймы
- GIMP, Blender
- Telegram Desktop
- KeePassXC, VeraCrypt
- Kdenlive, Audacity
- Flatpak приложения: JupyterLab, Obsidian, Video Downloader, PortProton

## ⚙️ Как использовать:
```bash
curl -O https://raw.githubusercontent.com/YOUR_USERNAME/arch-installer/main/install_programs.sh
chmod +x install_programs.sh
sudo ./install_programs.sh
```

##🔄 После перезагрузки:

```bash
flatpak install flathub org.jupyter.JupyterLab md.obsidian.Obsidian com.github.unrud.VideoDownloader ru.linux_gaming.PortProton -y
```
