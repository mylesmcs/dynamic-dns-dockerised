# dynamic-dns-dockerised

<div>
    <!-- Stability -->
    <img src="https://img.shields.io/badge/stability-experimental-orange.svg?style=flat-square">
</div>

## Description
The project aims to provide an easily deployable dynamic DNS (DDNS) service via docker. 

The docker deployment consists of the following containers:
* BIND - DNS server
* API - API build on Python3/Flask
* MARIA - Storage of user credentials and accout info
* NGINX - uWSGI proxy for API service

## Installation
1. Execute config-gen.sh and follow the prompts to generate the neccesary configuration files
1. docker-compose up

## Usage
Usage

## Tasks/Todo
- [ ] WebUI - create accout, login, display records, update records
- [ ] API - response/error messages for requests sent to server

