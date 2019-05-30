# jenkins-on-vagrant-with-ansible

## About

Deploys [Jenkins](https://jenkins.io/) using [Ansible](https://www.ansible.com/) on a [Vagrant](https://www.vagrantup.com/) box running [Ubuntu](https://www.ubuntu.com/). 


---

## Getting Started

### Prerequisites

- Ensure Vagrant is installed on your host machine.

### Start here

1. Uncompress the contents of the .zip file.
2. Open the root folder in your Terminal.
3. Run: ```vagrant up ```

---

## Troubleshooting

If you are having issues installing Jenkins then the information below may be of some assistance. 

### Versioning

At the time of writing the current stable versions are:

- Jenkins: 2.164x LTS
- Vagrant: 2.2.4
- Ansible: 2.7.10
- Ubuntu: 18.04 LTS

The installation process and syntax of these systems can change over time. You may have success by downgrading back to a previous stable version.

### Debug Information

If Ansible is failing then you can get more detailed debug information by toggling the verbose output setting and re-running the installation process. To do this, edit the ```Vagrantfile``` to read:
```ansible.verbose = true```. 
