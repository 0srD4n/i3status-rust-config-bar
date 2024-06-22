# i3status-rust Modern Configuration for i3wm
<p>
<b>Hallo, i3status-rust with</b> *Modern Themes* Configuration  This configuration is designed to bring a sleek, modern look and enhanced functionality to your i3status bar. Whether you are a developer, a power user, or someone who loves customizing their workspace, <b>this config is tailored to meet your needs.</b>

# custom block 
more information about i3 status-rust [docs](https://docs.rs/i3status-rs/latest/i3status_rs/blocks/index.html) - i3status-rust
you can read before installation

# Features
  * **Brightness Control**
  * **Volume Management**
  * **Network Monitoring**
  * **IP**
  * **monitor storage**
  * **Battery Status**
  * **Customizable Modules**
# Installation
 1.  Clone the Repository:
```bash
git clone https://github.com/username/i3status-rust-modern-config.git
cd i3status-rust-modern-config
```
 2. Copy Configuration Files:
```bash
cp config.toml ~/.config/i3status-rust/config.toml 
```
 3. Install Dependencies :
```bash
pacman -Syyu - < requirements.txt
```
 4. Reload i3-wm :
```bash
i3-msg reload
```
## config i3wm-desktop
<p>apply your status bar</p>

```bash
vim ~/.config/i3/config
```
change you config i3wm bar
```bash
bar {
    status_command i3status-rs /path/to/your/config.toml
    mode dock
```
Restart your desktop
```bash
i3-msg reload
```
# preview 

* default conf

![preview](preview.png)

