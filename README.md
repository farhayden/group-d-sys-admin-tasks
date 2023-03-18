# Group-D-System-Admin-Tasks

Welcome to the group-d repository for operations engineering 2.

- Ticket documentation can be found in the ` Wiki ` section.

## Team Members

- Greg Seal
- Francis Hayden

## Group-d Server Details

- Management Server IP address ` 68.218.47.185 ` (Puppet Master)
- Application Server IP address ` 68.218.47.211 ` (Puppet Agent)
- Backup Server IP address ` 68.218.47.144 ` (Puppet Agent)
- Database Server IP address ` 68.218.47.162 ` (Puppet Agent)

## SSH Into Servers Using Bash

 - open a ` git bash ` terminal
 - type command: ` ssh group-d@ ` followed by the IP address of the server you wish to connect to. For example `ssh group-d@68.218.47.211`
 - enter the servers password when prompted
 
 ## Useful Commands / Locations
 
 Refresh puppet on agent nodes ` sudo /opt/puppetlabs/bin/puppet agent --test ` alias: ` run-puppet `
 
 Site.pp (to manage modules run on each node) ` /etc/puppetlabs/code/environments/production/manifests/site.pp `
 
 Modules folder (add modules here) `/etc/puppetlabs/code/modules `
 
 ## Module Structure

```
 module_name
   ├── files
   ├── templates
   │      └── module_name.conf.erb
   └── manifests
          └── init.pp
```

