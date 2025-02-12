# RestLink UI - User Interface for the RestLink System

# This UI facilitates seamless interactions for truck drivers within 
# the platoon management system, ensuring an intuitive and efficient experience.

# ===========================
# DOWNLOAD AND SETUP
# ===========================

# Download the RestLink UI into your workspace on a Linux system:
wget -P ~/your_workspace/src https://github.com/restlink-hadi-miri/restlink_ui/blob/main/restlink_ui.zip

# Navigate to the src directory:
cd ~/your_workspace/src

# Extract the ZIP file:
unzip restlink_ui.zip -d restlink_ui

# Move to your ROS 2 workspace:
cd ~/your_workspace

# Build the package:
colcon build

# Source the workspace:
source install/setup.bash

# ===========================
# FILE STRUCTURE
# ===========================

# The restlink_ui folder contains the following:

# Folders:
# - __pycache__/   : Compiled Python files
# - resource/      : UI resources
# - restlink_ui/   : Main UI source code
# - test/          : Testing files and scripts

# Files:
# - CONTRIBUTING.md : Contribution guidelines
# - LICENSE         : Project license details
# - MANIFEST.in     : Defines package data for distributions
# - package.xml     : ROS package configuration file
# - setup.cfg       : Python packaging configuration
# - setup.py        : Package installation script

# ===========================
# USAGE
# ===========================

# To run the UI as part of the RestLink system, use:
ros2 run restlink_ui restlink_ui

# ===========================
# PROJECT DETAILS
# ===========================

# Author       : Hadi Miri
# Year         : 2025
# Institution  : Coburg University of Applied Sciences
# Team         : RestLink Team
