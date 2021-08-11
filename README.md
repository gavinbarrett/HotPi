## Description
This repo contains a script for checking CPU and GPU temperatures on the Raspberry Pi 3 and 4.


## Requirements

1. Download the script
    ```bash
	curl -O https://raw.githubusercontent.com/gavinbarrett/HotPi/master/hotpi
	```
2. Add execute permissions
	```bash
    sudo chmod +x ./hotpi
	```
3. Place the script somewhere in your $PATH
	```bash
    mv ./hotpi ~/.local/bin/
	```
4. Add user to the `video` group
	```bash
    sudo usermod -aG video <user>
	```

## Usage
	$ hotpi
    CPU Temperature  =>  46'C
    GPU Temperature  =>  44'C
