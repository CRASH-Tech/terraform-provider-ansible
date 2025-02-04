================================================
The Terraform Provider for Ansible Release Notes
================================================

.. contents:: Topics

v1.3.1
======

Bugfixes
--------

- make args & extra_vars sensitive.

v1.3.0
======

Minor Changes
-------------

- resource/ansible_playbook - Provider should failed with proper message when ansible is not installed (https://github.com/ansible/terraform-provider-ansible/issues/35).

Bugfixes
--------

- ensure extra vars are quoted (https://github.com/ansible/terraform-provider-ansible/pull/57).

v1.2.0
======

Release Summary
---------------

The terraform-provider-ansible v1.2.0 includes minor bugfixes and improvements.

Minor Changes
-------------

- Update dependencies (google.golang.org/grpc and golang.org/x/net) to resolve security alerts https://github.com/ansible/terraform-provider-ansible/security/dependabot (https://github.com/ansible/terraform-provider-ansible/pull/72).
- Updates the provider to use Go 1.21 (https://github.com/ansible/terraform-provider-ansible/pull/89)
- Updates the provider to use SDKv2 (https://github.com/ansible/terraform-provider-ansible/issues/39).

Bugfixes
--------

- provider/resource_playbook - Fix race condition between multiple ansible_playbook resources (https://github.com/ansible/terraform-provider-ansible/issues/38).
