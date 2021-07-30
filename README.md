<h1 align=center>Flutter On Linux</h1>

## Install Flutter & Dart using Git
```bash
cd ~
git clone https://github.com/flutter/flutter.git -b stable
```
## Launch in startUp
```bash
sudo nano /etc/profile
```

   ```bash
   # this will Set flutter & Dart in StartUp
   export PATH=$PATH:`pwd`/flutter/bin
   ```
   ```bash
   # this will Configure Linux desktop on flutter
   flutter config --enable-linux-desktop
   ```
## Restart 
## Check Installation
```bash
which flutter dart
```


## Required Packages 
```bash
sudo apt install clang cmake ninja-build pkg-config libgtk-3-dev
```


	

