# Ansible_HAproxy_on_AWS


Ansible playbook to Configure Reverse Proxy i.e. Haproxy and update it's configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory on AWS.

## Steps:

        1. Create the webserver group for webserver in the inventory file.
        2. Copy the haproxy.php and haproxy.cfg file in the locations given in haproxy.yml playbook.
        3. Run the Ansible playbook.
