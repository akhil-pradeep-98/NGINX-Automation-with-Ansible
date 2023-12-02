# NGINX-Automation-with-Ansible
Installing NGINX Server on Virtual Machines and Containers Using Ansible Automation Over AWS

#Introduction

In the realm of DevOps, automating infrastructure deployment and configuration is paramount. This project tackles the challenge of setting up a NGINX web server on both virtual machines and containers using Ansible.

#Objectives

- Hands-on Ansible Experience

- NGINX Installation and Configuration

- Comparative Infrastructure Management

#Prerequisites

- Basic Knowledge of AWS

- Ansible Installation

#Steps To Follow 

- Launch EC2 machine (Master and Client Machine)

- Install Ansible on the Master Machine 

- In Client Machine give access for ssh for the master machine.

- Create Inventory file with specify target hosts for VM

- Include connection information like IP addresses, SSH credentials.

- Create playbook.yaml file to install and configure NGINX

#Testing

Hit the public ip address of the Client Machine (It will show the NGINX Default page.)

