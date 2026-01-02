# aap-first-project
Repository for my first AAP Projects


### Playbook Strategy

- deploy_services.yml
  Deploys the full baseline of system services (chrony, rsyslog, nginx, firewalld, tuned).
  Used during initial provisioning and compliance runs.

- deploy_nginx.yml
  Deploys nginx only.
  Used for application-level changes and isolated updates without impacting system services.

