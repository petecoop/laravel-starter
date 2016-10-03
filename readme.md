# Laravel starter

**Requires [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html) to be installed**

- Clone or download the zip of this repo
- Rename the folder to the name of your project
- Create a `.env` file, copy the contents of `.env.example`
- Download the laravel homestead box (1.2GB) run: `vagrant box add laravel/homestead`
- Run: `vagrant up` - this will create and start the VM
- Navigate to http://localhost:8000, you should see the Laravel welcome screen

This uses a per-project Homestead setup: https://laravel.com/docs/5.3/homestead#per-project-installation

### Basic Vagrant usage

These commands must be ran in your project folder:

- `vagrant up` to start the VM
- `vagrant halt` to shutdown the VM
- `vagrant destroy` to delete the VM and all of it's data
- `vagrant ssh` to ssh into the VM