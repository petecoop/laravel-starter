# Laravel starter

## Requirements

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- PHP [Windows Install](http://windows.php.net/download/), for Mac use HomeBrew [instructions](#mac-php-install)
- [Composer](https://getcomposer.org/)

- Clone or download the zip of this repo
- Rename the folder to the name of your project
- Run `composer install`
- Run `php vendor/bin/homestead make`
- Download the laravel homestead box (1.2GB) run: `vagrant box add laravel/homestead`
- Run: `vagrant up` - this will create and start the VM
- Navigate to http://localhost:8000, you should see the Laravel welcome screen
- You're all setup!

This uses a per-project Homestead setup: https://laravel.com/docs/5.3/homestead#per-project-installation

### Basic Vagrant usage

These commands must be ran in your project folder:

- `vagrant up` to start the VM
- `vagrant halt` to shutdown the VM
- `vagrant destroy` to delete the VM and all of it's data
- `vagrant ssh` to ssh into the VM

## Mac PHP Install

- Install [HomeBrew](http://brew.sh/)
- `brew tap homebrew/homebrew-php`
- `brew install php70`