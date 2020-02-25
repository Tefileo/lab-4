# Multi Machine Vagrant with Ansible

## Timings

120 - 180 Minutes

## Summary

The sample application has the ability to connect to a database. We need to provision our development environment with a vm for the application and one for the database.

Vagrant is capable of running Ansible playbook for provisioning VM.

## Tasks

* Research how to use Ansible playbook to replace Bash shell scripts used in lab-1 in vagrant environment
* Use Ansible playbook to create app and db machine as done in lab-1
* You will need to start from the result of lab-1 to continue with this lab
* Start the app and ensure that the /posts route is now connected correctly as does in lab-1

## Notes

You can test your app and database are working correctly by running the test suite in the test folder. There are two sets of tests. One for the app VM and one for the db VM. Make them all pass.

```
cd test
rake spec
```
venv/
.idea
