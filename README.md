# Sitemap Generator
Automatic generate standard XML sitemap (http://example.com/sitemap.xml) that supports the providers including Google, Yahoo, MSN, Ask.com, and others.

* Contributors: **mattrude**
* Author URI: **http://mattrude.com/**
* Plugin URI: **http://technology.mattrude.com/projects/sitemap-wp-plugin/**
* Requires at least: **3.3**
* Tested up to: **3.3**
* Stable tag: **1.1**

## Description
This plugin will create a sitemap for your WordPress site (http://example.com/sitemap.xml). No files are stored on your disk, the sitemap.xml file is generate as needed, like your feeds.  No UI to speak of, just drop in place and your good to go.

This plugin was original created for a WordPress Multi-Site setup (with the files placed in the mu-plugins folder).  This plugin also works well on Single User setups of WordPress as well.

The Sitemap Generator Plugin is licensed under the [GNU General Public License, version 2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) as published by the [Free Software Foundation, Inc](http://www.gnu.org/).

## Installation
As with most WordPress plugins, there is two ways of installing this plugin.

### Primary Option

1. Download the latest version of this plugin from the [download page](https://github.com/mattrude/wp-plugin-sitemap-generator/downloads).
1. Go to your WordPress Dashboard and login as an Admin
1. From your Dashboard go to `Plugins` section on the left hand side and select `upload` from the top.
1. Find the downloaded plugin in the upload pop up window
1. Click the `Install Now` link and follow the instructions.

### Secondary Option

1. Log onto your web server via SSH or Telnet, and go into the directory that holds your WordPress install.
1. Move into your plugins directory `cd wp-content/plugins`
1. Clone the current revision with the command `git clone git://github.com/mattrude/wp-plugin-sitemap-generator.git`

## Changelog

### Trunk
* Replace `get_post_time()` with `get_post_modified_time()`, Ticket #1

### Version 1.1
* Added filter to remove trailing slash from sitemap.xml, props [Ov3rfly](http://technology.mattrude.com/2011/10/07/wordpress-sitemap-generator-plugin/#comment-569)

### Version 1.0
* Initial Version

## License

    GNU GENERAL PUBLIC LICENSE
    
    Version 2, June 1991
    
    Copyright (C) 1989, 1991 Free Software Foundation, Inc.  
    51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA
    
    Everyone is permitted to copy and distribute verbatim copies
    of this license document, but changing it is not allowed.
