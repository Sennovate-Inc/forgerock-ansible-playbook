# ForgeRock-ansible-playbook

A public fork of Sennovate's internal Ansible playbook to set up ForgeRock AM for development and testing.

<p align="center">
  <a href=" https://github.com/Sennovate-Inc/forgerock-ansible-playbook/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true" alt="Pull Requests">
  </a>
  <a href="https://twitter.com/Sennovate" target="_blank">
    <img src="https://img.shields.io/twitter/follow/Sennovate.svg?logo=twitter">
    </a>
</p>

## Description
This playbook aims to help build test and development environments for ForgeRock AM through an ansible playbook in order to reduce deployment time.

## Prerequisites

- Ansible
- Ubuntu 18.04 and above
- Root access to run the script

## Installation

ForgeRock ansible playbook requires ansible to be installed and running the `playbook.yaml` will automatically check requirements, download libraries and packages to install the ForgeRock AM 7.1.

To run a specific version of ForgeRock AM, update the vars.yaml with the specific ForgeRock AM version.

To run the playbook and install ForgeRock AM, follow the steps below:

1. Clone GitHub Repository
```
git clone git@github.com:Sennovate-Inc/forgerock-ansible-playbook.git
```
2. Switch to Repository Directory
```
$ cd forgerock-ansible-playbook
```
3. Execute Ansible script
```
$ ansible-playbook playbook.yaml
```
4. Access the server using the FQDN
```
http://FQDN 
```

## Usage

With this Ansible playbook you can now run and develop test environments to build POCs and get up and running with ForgeRock AM in just 2 minutes!

Default Installation version: `7.1.2 (latest)`

Versions supported: `7.1.2 and 7.1.1`

## Support

Sennovate will support and update the script for major releases of ForgeRock AM only.

For any issues during installation, raise an issue.

## Roadmap

This functionality will also be available with Single click deployment through [Sennovate+](https://www.plus.sennovate.com). Stay tuned for more updates and follow us on our Sennovate for latest updates. 👀 

## Contributing

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details and guidelines.

## License

This project is licensed under the [Common Development and Distribution License (CDDL)](LICENSE).

## About Sennovate

[Sennovate](https://sennovate.com/) delivers custom identity and access management solutions to businesses around the world. With global partners and a library of 1000+ integrations, we implement world-class cybersecurity solutions that save your company time and money. We offer a seamless experience with integration across all cloud applications, and a single price for product, implementation, and support. Have questions? The consultation is always free. Email hello@sennovate.com or call us at: +1 (925) 918-6618.

## Join Us

Do you love solving security challenges and have a strong background in cybersecurity and Identity and Access Management?
Join our team in this fast-paced, collaborative and fun environment where you get to work with smart people and use your innovative thinking to level up.📈

[Look at our Open Positions](https://sennovate.com/careers/)
