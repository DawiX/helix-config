# Helix config

## Install

```bash
HX_VERSION="23.03"
wget https://github.com/helix-editor/helix/releases/download/$HX_VERSION/helix-$HX_VERSION.tar.xz
tar -xf helix-$HX_VERSION.tar.xz
mv helix-23.03-x86_64-linux $HOME/.helix
ln -s /usr/bin/hx $HOME/.helix/hx
git clone git@github.com:DawiX/helix-config.git ~/.config/helix
```
