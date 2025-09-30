# Configuration Files

This folder contains all configuration files for the JetBot project.

## Contents

- **`config.txt`** - Main configuration file for line following and robot behavior
- **`optimized_config.txt`** - Optimized configuration settings
- **`rule_config.json`** - Rule-based behavior configuration
- **`map.json`** - Map data for navigation

## Usage

These configuration files are automatically loaded by the Python scripts. Make sure to update the file paths in your scripts if you move these files.

### Configuration File Locations

- Line following scripts look for `config/config.txt`
- Map navigation scripts look for `config/map.json`
- Rule-based scripts use `config/rule_config.json`
