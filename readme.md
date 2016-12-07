# Laravel starter

### Requirements

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- PHP
  - [Windows Install](http://windows.php.net/download/)
  - Mac Install:
    - Install [HomeBrew](http://brew.sh/) (it's amazing)
    - `brew tap homebrew/homebrew-php`
    - `brew install php70`
- [Composer](https://getcomposer.org/)

## Setup

- Clone or download the zip of this repo
- Rename the folder to the name of your project
- Run `composer install`
- Run `vendor/bin/homestead make`
- Create a `.env` file, copy the contents from `.env.example`
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

## Bugs? Questions?

[Open an issue](https://github.com/petecoop/laravel-starter/issues) and let me know!