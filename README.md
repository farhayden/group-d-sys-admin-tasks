# group-d-sys-admin-tasks

## Group-d Server Details

- Management Server IP address ` 68.218.47.185 ` (Puppet Master)
- Application Server IP address ` 68.218.47.211 ` (Puppet Agent)
- Backup Server IP address ` 68.218.47.144 ` (Puppet Agent)
- Database Server IP address ` 68.218.47.162 ` (Puppet Agent)

## SSH Into Servers Using Bash

 - open a ` git bash ` terminal
 - type command: ` ssh group-d@ ` followed by the IP address of the server you wish to connect to. For example `ssh group-d@28.218.47.211`
 - enter the servers password when prompted
 
 ## Useful Commands
 
 Refresh puppet on agent nodes ` sudo /opt/puppetlabs/bin/puppet agent --test `
