# Yeoman WordPress Generator

Yeoman generator for WordPress projects and plugins.

For more informations about Yeoman, see [Yeoman.io](http://yeoman.io/).

## Installation

    npm install -g generator-assembly-wp

## Documentation

### Init

    yo assembly-wp

Generates a new WordPress project with a starter theme and the files needed to use Yeoman. Once Yeoman is done, install your new WordPress project, and activate the theme in the admin panel.

Yeoman will ask you which version of WordPress you want to use (latest stable version by default), the starter theme and a few informations to make the theme ready be to used. Most of the defaults informations can be changed in the [config file](#configuration).

## Configuration

Yeoman-WordPress stores some defaults values so you won't have to type the same things every time you start a project. The first time you will use the generator it will create a config file with the informations you gave. These informations will be used as default values so you can override them during the init tasks. If you want to change the default values you can do it by editing the config file located in `~/.yeoman-wordpress/config.json`.
