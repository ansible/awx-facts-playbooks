# awx-facts-playbooks
Repository containing playbooks to support fact scanning in Ansible Tower and AWX.

Previously these playbooks were built-in to Ansible Tower. With the removal of the System Tracking feature we've made
them available outside of the project. The scan modules are still included in Tower and AWX so this playbook can be used
with those modules from within Tower and AWX to populate extra fact data that wouldn't normally be available.
