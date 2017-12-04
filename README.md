# tor [![Open in Cloud9](https://img.shields.io/badge/Open%20in-Cloud9-blue.svg?style=flat-square)](https://c9.io/auth/github?r=https%3A%2F%2Fc9.io%2Fopen%2F%3Fclone_url%3Dhttps%253A%252F%252Fgithub.com%252Fdenzuko-ansible-roles%252Ftor.git)

Basic out of bounds ssh tor service which reports nodes onion names when completed

## Installation
$ ``` ansible-galaxy install denzuko.tor ```

## Requirements
* `ansible=>2.2`
* `Linux server`

## Files
This module Installs /etc/tor/torrc and [tor daemon](https://www.torproject.org/docs/documentation.html.en)
