# Tomcat Installation Script for Ubuntu EC2 Instances on AWS

## Overview

This script automates the installation and configuration of Apache Tomcat on a newly created Ubuntu EC2 instance on Amazon Web Services (AWS). It simplifies the setup process, making it ideal for users deploying Tomcat on Ubuntu instances in the AWS cloud environment.

## Features

- Streamlined installation of Apache Tomcat 9
- Automatic update and upgrade of system packages
- Java Development Kit (JDK) installation
- Creation of symbolic links for Tomcat startup and shutdown
- Configuration of Tomcat server settings
- Addition of an admin user to Tomcat users

## Prerequisites

- An AWS EC2 instance running Ubuntu
- Sudo access on the EC2 instance
- Internet connectivity on the instance for package downloads

## Usage

1. Copy the script or clone to your Ubuntu EC2 instance.
`git clone https://github.com/Chriscloudaz/tomcat-installation-script-ubuntu-ec2/` 

2. Set the preferred location for your logfile.

3. Set your preferred username and password under Tomcat users. 

4. Run the script with sudo permissions.
`sudo bash tomcat-install-script.sh`

Please feel free to reach out on chriscloudaz@gmail.com 
