# iOS_oh-my-zsh

This is a forked Version of [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) optimized for jailbroken iOS devices.

## Bugs and enhancements

For bug reports or enhancements, please open an [issue](https://github.com/A2nkF/dorfctl/issues) here.

## Installation

Install following packages from Cydia:

```    
   wget 
   Z Shell
   git
   apt 0.7 Strict (not the pre-installed apt 0.7 Strict(lib))
   cURL
   nano
   SSLPatch (only if your device is supported)
``` 



If your iDevice doesn't support SSL you will have to download this repo manually.

Devices with SSL support:

`git clone https://github.com/A2nkF/oh-my-zsh.git`

Devices without:

`wget https://github.com/A2nkF/oh-my-zsh/archive/master.zip --no-check-certificate && mv oh-my-zsh-master .oh-my-zsh`
 

```shell
sh -c "$(wget https://raw.githubusercontent.com/A2nkF/oh-my-zsh/master/tools/install.sh -O -)"
```
