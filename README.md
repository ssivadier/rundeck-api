# README

This script allows you to:
- list projects
- list all jobs in a project (id, name and group)
- remove all jobs from a project
- export all jobs and history(activity) from a project
- import all of this back in

## Usage

You need to create a token to use this. Please refer to rundeck documentation for this: http://rundeck.org/docs/api/index.html#token-authentication

This script has been made for 2 servers, as one is the backup of the other. But I believe it's really easy to use it on just one server instead.

Anyhow, that's why you have a test for VIP presence. It is a virtual IP used for HA. If you don't use corosync, you'd better remove this test.

Please change the values of the readonly variables defined at the begining of the script to better suit your environment.

Hope this might be helpful.
