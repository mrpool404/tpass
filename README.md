# tpass
It is a python based terminal Password manager for linux. You can store multiple passwords organised in groups. Credentials are encrypted using AES. You can also store additional details attached to a credential in plain text or encrypted format. Good Practise to store password would be to use the site name as the credential name and store the username as an addtitional detail in encrypted format.

## Prerequisites
* Python3
* pip3 (If you wish to install the required packages manually then no need of pip3)

### Installing

clone the repository or download the zip and unzip it
open the terminal in the downloaded directory
run install.py to install dependencies 
```
$ ./install.py
```
If you encounter error while installing dependencies try installing them manually and run the install.py again.
After successfull installation of dependencies run 'tpass' from a new shell
```
$ tpass
```
Follow the initialisation procedure.

You can use help command to view the available commands and their functions

### Deployment and migration
All the data is stored in 'data' directory. When you wish to migrate to a new system just copy the data directory and place it aywhere in the new system. Install and initialise tpass in the new system. When asked to import files during initilisation enter 'y' and give the path to the copied directory and you would be able migrate it to the new system.

## License

This project is licensed under the MIT License.
