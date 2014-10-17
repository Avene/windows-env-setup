windows-env-setup
=================

windows setup procedure

## install chocolatey
```
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

## install apps via chocolatey
```
choco install choco_packages.config
```
_Note that it is necessary to run command prompt as administrator_
