# packer-windows
This repository contains Windows templates that can be used to create boxes for Vagrant using Packer (version 1.5.6).


. Download packer v1.5.6 from https://developer.hashicorp.com/packer/downloads?host=www.packer.io
Run command `.\packer.exe build .\windows_10.json`

In case of errors on a recent version of packer, run fix command:
.\packer.exe fix .\windows_10.json > .\windows_10_fixed.json
