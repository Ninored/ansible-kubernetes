# Ansible project for Homelab deployment of Kubernetes

This configuration doesn't work with multiple `Master`.

Replace host in `hosts.ini` with at only one master and any number of worker and run.

```sh
ansible-playbook ./site.yml
```

This script will install Kubernetes without Traefik.
And copy the Kubernetes configuration file as `./k3s-config`
