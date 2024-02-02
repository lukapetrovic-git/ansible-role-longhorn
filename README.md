# ansible-role-longhorn
Ansible role to install longhorn on k8s cluster.

# Requirements
- Ansible 2.13 or later
- Helm 3 installed on server passed to longhorn_delegate_to (Can be Ansible Controller or Cluster Node)

## Collections
kubernetes.core >= 2.4.0
community.general >= 8.3.0

# Tested on
- Ubuntu 20.04 LTS
- Ubuntu 22.04 LTS

# Role Variables
All settable variables with explanations and links are located in the defaults/main.yml

## TODO
- Create Action to publish to Anisble Galaxy
- Write Molecule tests
- Create Action to run Molecule tests
- Create CI
- Add examples to readme
- Add functionality to upgrade/delete Longhorn from cluster