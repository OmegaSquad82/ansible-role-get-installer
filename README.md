# ansible-role-get-installer

## Description

Fetches <tool>-specific installer script from <url>, executes it and checks success by calling "<tool> version". This ensures that a) the recommended procedure to install the tool is being executed and b) the current version has been installed on the local machine.

## Security

Executing an installer script from a short <url> with root privileges is potentially dangerous. You may opt out of this and are welcome to install the tools manually.

## Developed for

Easy setup of some of [@alexellis](https://github.com/alexellis/) wonderful tools:

- [k3sup](https://k3sup.dev/ "from Zero to KUBECONFIG in < 1 min")
- [arkade](https://get-arkade.dev/ "Kubernetes apps, the easy way")
