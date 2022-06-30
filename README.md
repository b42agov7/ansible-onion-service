# ansible-onion-service
Automate the set up of your Onion Service. Install Tor and deploy your Onion Service quickly autonomously thanks to Ansible.
Works for Trisquel 10, Debian 11 and Ubuntu 22.04 LTS.

## How to use it

- Step 1: Configure your hosts in ansible-onion-service.yaml.
- Step 2: Configure your remote user in ansible-onion-service.yaml.
- Step 3: Configure your website name in ansible-onion-service.yaml.
- Step 4: Run the playbook. Like this: ```ansible-playbook --ask-become-pass /PATH/TO/ansible-onion-service.yaml```.

## Security advice and tips

To secure your Onion Service as well as your server, you must follow this guide.
- Basic recommendations, click [here](https://community.torproject.org/onion-services/advanced/opsec/).
- To secure your server, click [here](https://gitlab.torproject.org/legacy/trac/-/wikis/doc/OperationalSecurity).
- To improve the security of your Onion Service with Vanguards, click [here](https://blog.torproject.org/announcing-vanguards-add-onion-services/).
- To scan your Onion Service to find any vulnerabilities, click [here](https://onionscan.org/).

*b42agov7*
