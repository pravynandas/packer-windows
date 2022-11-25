# packer-windows
This repository contains Windows templates that can be used to create boxes for Vagrant using Packer.


. Download packer from https://developer.hashicorp.com/packer/downloads?host=www.packer.io
Run command `.\packer.exe build .\windows_10.json`

In case of errors run fix command:
.\packer.exe fix .\windows_10.json > .\windows_10_fixed.json
