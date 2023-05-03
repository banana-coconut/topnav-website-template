# Topnav Website

A website template with a top navigation bar.

## Installation

### Via GitHub

Click on the Code tab then click on the green button also named Code,
click on the Local tab if not already there and then click on on the
Download ZIP button, this will download the code in a compressed ZIP
file so you will need a archiving program to unzip it.

### Via Command Line

#### With Wget

```bash
wget https://raw.githubusercontent.com/Banana-Coconut/topnav-website/master/index.html 
https://raw.githubusercontent.com/Banana-Coconut/topnav-website/master/styles.css
```
#### With curl

```bash
curl -O https://raw.githubusercontent.com/Banana-Coconut/topnav-website/master/index.html 
https://raw.githubusercontent.com/Banana-Coconut/topnav-website/master/styles.css
```
## Editing

## Usage

### Locally

IMPORTANT: THIS ONLY WORKS ON DEBIAN AND DEBIAN BASED DISTROBUTIONS LIKE LINUX MINT

#### Installing the Server
```bash
cd /home/$USER
sudo apt update
sudo apt install nginx
sudo cp /home/$USER/index.html /var/www/html/
sudo cd /home/$USER/styles.css /var/www/html/
sudo rm index.html styles.css 
```
