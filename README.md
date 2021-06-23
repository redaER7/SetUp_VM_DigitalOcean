## Table of contents
* [Create VM aka droplet](#Create-VM-aka-droplet)
* [Technologies](#technologies)
* [Setup](#setup)

Linux-Remote Server are Linux-based virtual machines (VMs) that run on top of virtualized hardware
VMs are managed using a terminal and SSH. You’ll need to have an SSH client and, optionally, an SSH key pair. Clients generally authenticate either using passwords (which are less secure and not recommended) or SSH keys (which are very secure and strongly recommended).
We recommend you use SSH keys to connect to your VM.

## Create VM aka droplet
Create DigitalOcean account from https://cloud.digitalocean.com/registrations/new

Log in to the control panel https://cloud.digitalocean.com/login , click the green Create button in the top right to open the create menu.
![Image1](./images/image1.png)

Click Droplets to open the Droplet create page. Choose your Droplet’s configuration, its operating system, howmemory, and which features (like backups or monitoring) to enable.

In the Choose a plan section,choose the amount of RAM, storage space, and CPU cores your want.

In the Authentication section, choose the method you want to use to log in to your Droplet. There are two options:

- SSH keys, which provide more security than a password.
- Password, which allows you to create your own password for the new Droplet.


## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
	
## Setup
To run this project, install it locally using npm:

```
$ cd ../lorem
$ npm install
$ npm start
```

![Algorithm schema](./images/image1.png)
