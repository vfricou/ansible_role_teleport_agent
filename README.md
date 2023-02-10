# Ansible Role: teleport-agent

# Disclaimer

I couldn't be responsible with any production issues if you use this role without any prior tests.  
This role is designed for my proper environment and possibly not correspond to your.

The master branch is development branch. Use only release/* branches for production.

# Introduction

This role is designed to perform teleport agent installation and configuration for ssh access on GNU/Linux servers.  
It's structured and do tasks according to my own requirements and production needs.  
Feel free to fork and update this according to your requirements.

# Supported OS

**Debian** :
- 10
- 11

**Ubuntu** :
- 20.04
- 22.04

**RHEL**/**RockyLinux**/**AlmaLinux** :
- 8
- 9

# Variables

Read content of [defaults variables](./defaults/main.yml) to get configurables variables

# Requirements

## On target OS

You need to have python3 package installed on remote OS to use this role.

# Actions

TODO

# Changelog

To clearest and updated changelog, I encourage you to see pull requests with flags "feature".

# Roadmap

You could refer to milestones to full current roadmap.

### v1.0.0

Perform teleport agent installation and configuration with dynamic cluster token generation.
